# Tecniche di Design — Landing Page Maleducati Finanziari

## Filosofia
Ogni scelta di design serve la conversione, non l'estetica. La landing ha un solo obiettivo: trasformare chi arriva in un iscritto al percorso. Questo guida ogni decisione — dai colori alla tipografia, dalla gerarchia delle card al posizionamento dei bottoni.

---

## Brand visivo

| Elemento | Valore | Uso |
|----------|--------|-----|
| `--mf-navy` | `#003a64` | Sfondo dominante, testi su chiaro, authority |
| `--mf-blue` | `#54a2d2` | CTA, accenti, link, badge |
| `--mf-light` | `#a9cee8` | Sfondi sezioni alternate, testi su navy |
| `--mf-white` | `#ffffff` | Respiro, testi su navy, sezioni neutre |
| Font titoli | Antonio (Google Fonts) | H1, H2, H3 — condensato, forte, autorevole |
| Font body | DM Sans (Google Fonts) | Paragrafi, liste, label — leggibile, moderno |

---

## Regole anti-AI slop

- **Mai** gradienti viola su bianco
- **Mai** layout simmetrici con 3 colonne identiche senza gerarchia visiva
- **Mai** card tutte uguali — la card Premium deve dominare visivamente su Plus ed Exclusive
- **Mai** sfondi piatti monocromatici — usare sempre gradienti radiali asimmetrici in `#003a64` o `#54a2d2` a opacità 10–15%, posizionati fuori centro (in alto a sinistra, in basso a destra, mai al centro)
- **Mai** Inter, Arial o Roboto per i titoli

---

## Regole di conversione

1. **Urgency bar fissa in cima** — sempre visibile con countdown live. Non può essere scrollata via. Deve ricordare costantemente la scadenza del 12 aprile.

2. **CTA ripetuta ogni 2–3 sezioni** — non aspettare che il lettore arrivi al pricing. Chi è pronto prima converte prima.

3. **Bottoni CTA** — sfondo `#54a2d2`, testo bianco, hover scurisce a `#3d8ab8` con scale 1.02 e transizione 300ms. Mai bottoni con bordo trasparente per le CTA primarie.

4. **Card Premium in evidenza** — bordo `#003a64` pieno 2px, padding extra, badge "⭐ Più scelta" sopra la card, dimensione colonna 1.08fr nella griglia vs 1fr per le altre. Su mobile: appare prima delle altre.

5. **Prezzi barrati** — il prezzo originale barrato crea un'ancora cognitiva che fa percepire il prezzo attuale come un'occasione.

6. **Obiettivo per sezione**:
   - Hero → cattura attenzione (rettiliano: minaccia + protezione)
   - Problema → crea dolore (limbico: rispecchia la frustrazione)
   - Storia → costruisce fiducia (rettiliano → limbico)
   - 3 recensioni → emozione e identificazione (limbico puro)
   - Programma → crea desiderio (neocorteccia: razionalizza l'acquisto)
   - Pricing → chiude (neocorteccia: valuta le opzioni)
   - Chi siamo → rinforzo fiducia
   - 9 recensioni → prova sociale massiva
   - CTA finale → rilancia con urgenza

---

## Struttura PNL (ordine obbligatorio)

```
RETTILIANO (sopravvivenza, fiducia, allerta)
   Hero + Problema + Storia

LIMBICO (emozioni, connessione, identificazione)
   3 recensioni intermedie

NEOCORTECCIA (logica, metodo, confronto)
   Programma + Pricing + Chi siamo

CHIUSURA URGENZA (rettiliano + limbico + urgenza reale)
   9 recensioni + CTA finale con countdown
```

---

## Stack tecnico

| Componente | Soluzione |
|-----------|-----------|
| Font | Google Fonts CDN (Antonio + DM Sans) via Code Injection Header |
| Animazioni scroll | GSAP 3.12.5 + ScrollTrigger da `cdnjs.cloudflare.com` |
| Countdown | JavaScript puro, nessuna libreria |
| CSS custom | Design > Custom CSS in Squarespace |
| Layout card e griglie | CSS Grid con `display: grid` |
| Micro-interazioni | CSS `transition`, `transform: scale(1.02)` su hover |

---

## Principi visivi

- **Profondità, non piattezza** — ogni sezione su navy ha un gradiente radiale asimmetrico. La posizione varia sezione per sezione per evitare monotonia.
- **Spazio bianco generoso** — il bianco tra i blocchi fa respirare il contenuto e aumenta la leggibilità percepita.
- **Gerarchia tipografica netta** — H1 grande (56–72px su desktop), H2 medio (36–46px), body 16–18px. Su mobile scalano proporzionalmente con `clamp()`.
- **Mobile-first** — l'80% del traffico arriva da mobile. Griglia 3 colonne → stack verticale. Padding ridotti. Font scalati. Bottoni a larghezza piena.
