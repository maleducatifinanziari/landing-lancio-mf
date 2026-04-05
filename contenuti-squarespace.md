# Contenuti e Istruzioni — Landing Page Squarespace
## Maleducati Finanziari — Lancio "Il Tuo Budget a Prova di Bomba"

---

> **Come leggere questo documento**
> Per ogni sezione trovi:
> - **Blocco Squarespace** → quale tipo di blocco aggiungere
> - **Classe CSS** → il codice da copiare nel campo "CSS Class"
> - **Istruzioni passo per passo** → cosa fare in Squarespace
> - **Testo esatto** → copia e incolla direttamente

---

## PRIMA DI INIZIARE — Come aggiungere una classe CSS a una sezione o un blocco

**Per una SEZIONE intera:**
1. Passa con il mouse sulla sezione → compare una barra grigia con le opzioni
2. Clicca l'icona **Modifica sezione** (la matita)
3. Nella colonna di destra vai su **Avanzate**
4. Nel campo **CSS Class** incolla la classe indicata

**Per un BLOCCO singolo (testo, immagine, bottone):**
1. Clicca sul blocco per selezionarlo
2. In alto a destra clicca l'icona **Design blocco** (le due sfere)
3. Vai su **Avanzate**
4. Nel campo **CSS Class** incolla la classe indicata

---
---

## SEZIONE 0 — Urgency Bar (automatica)

> **Non devi fare nulla qui.** La barra di urgenza con il countdown viene creata automaticamente dallo script nel file `header-injection.html`. Appare in cima alla pagina non appena incolli il codice in Code Injection.

---
---

## SEZIONE 1 — Hero

**Obiettivo psicologico:** Rettiliano — minaccia esterna + promessa di protezione. Cattura subito l'attenzione con un'affermazione che rispecchia la realtà del lettore.

---

**Blocco Squarespace:** Aggiungi una nuova **Sezione** di tipo **Cover** o **Banner** (è la prima sezione della pagina)

**Classe CSS da aggiungere alla SEZIONE:** `mf-hero`

---

**Istruzioni:**
1. Crea una nuova sezione all'inizio della pagina
2. Scegli il layout **Cover** (quello con il testo centrato su sfondo) oppure **Banner**
3. Aggiungi la classe `mf-hero` alla sezione (vedi sopra come fare)
4. All'interno della sezione aggiungi un blocco **Testo** e un blocco **Bottone**
5. Per il blocco Testo, copia il contenuto qui sotto
6. Per il blocco Bottone, imposta testo e link come indicato
7. Aggiungi la classe `mf-btn` al blocco Bottone

---

**TESTO DA COPIARE — blocco Testo:**

```
I PREZZI SALGONO. I GUADAGNI NO. L'INSTABILITÀ CRESCE.

Smetti di arrivare a fine mese con il fiato corto.

Il sistema in 5 fasi per costruire la tua sicurezza economica — anche se parti da zero e non sai da dove cominciare.
```

*(La prima riga va formattata come testo piccolo in maiuscolo — nel blocco Testo seleziona quella riga e riducila a dimensione piccola. Il titolo principale è la seconda riga, formattala come H1. La terza riga è il paragrafo sottostante.)*

---

**BOTTONE CTA:**
- Testo bottone: `Sì, voglio iniziare →`
- Link: `https://esmerise.com/maleducatifinanziari/register?p=8274`
- Classe CSS del bottone: `mf-btn mf-btn-large`

---

**Sotto il bottone — aggiungi un secondo blocco Testo piccolo:**
```
Iscrizioni aperte fino al 12 aprile alle 23:59. Poi si chiudono.
```
*(Classe CSS su questo blocco: `mf-hero-sub`)*

---
---

## SEZIONE 2 — Il Problema

**Obiettivo psicologico:** Limbico — amplifica il dolore. Il lettore deve riconoscersi e sentire che questa landing parla di lui.

---

**Blocco Squarespace:** Aggiungi una nuova **Sezione vuota** dopo l'Hero

**Classe CSS da aggiungere alla SEZIONE:** `mf-problema mf-animate`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota dopo l'Hero
2. Aggiungi la classe `mf-problema mf-animate` alla sezione
3. Inserisci un blocco **Testo** e copia il contenuto qui sotto

---

**TESTO DA COPIARE:**

```
Quanto ti rimane davvero ogni mese?

Pensa ai soldi che entrano. Adesso togli l'affitto o il mutuo. Togli le bollette. Togli la spesa. Togli le rate.

Quello che rimane — e solo quello — sono i soldi su cui hai davvero potere.

E ogni mese sono sempre meno.

Perché i prezzi salgono, i guadagni no. E se non hai un sistema, basta una spesa imprevista — l'auto che si rompe, il frigorifero, il dentista — per mandare tutto in crisi.

E si ricomincia da capo.

Ogni. Singolo. Mese.
```

*(Formatta "Quanto ti rimane davvero ogni mese?" come **H2**. Il resto come paragrafi normali. Metti in grassetto "Ogni. Singolo. Mese.")*

---

**Sotto il testo, aggiungi un secondo blocco Testo per la seconda headline:**

```
Non è colpa tua.
Nessuno ti ha mai insegnato come farlo.
```

*(Formattalo come **H2** o testo grande)*

---
---

## SEZIONE 3 — La Storia

**Obiettivo psicologico:** Rettiliano → Limbico — costruisce fiducia attraverso la vulnerabilità reale di Dora e Davide.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-storia mf-animate`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota
2. Aggiungi la classe `mf-storia mf-animate`
3. Inserisci un blocco **Testo** con il contenuto qui sotto
4. Aggiungi una vostra **foto** con un blocco **Immagine** a fianco del testo (layout a 2 colonne)

---

**TESTO DA COPIARE:**

```
Anche noi eravamo così.

10 anni fa Dora e Davide erano dei veri maleducati finanziari.

Nessun piano. Nessun risparmio. Lo schema era sempre lo stesso: arrivava lo stipendio, si iniziava a spendere, si tirava il freno a mano quando i soldi stavano finendo, e si aspettava quello dopo.

Il momento di svolta è arrivato quando stavano per sposarsi. Data fissata, tutto organizzato. E da un giorno all'altro si rompe l'auto. Dovevano comprarla nuova.

Non avevano un euro da parte.

Zero.

Da quel momento hanno iniziato a studiare e costruire il sistema che li ha cambiati. Oggi lo insegnano a migliaia di persone. E hanno scritto un libro.

"Quando tutto va bene, ti prepari. Quando qualcosa va storto, ti ringrazi di averlo fatto."
```

*(Formatta "Anche noi eravamo così." come **H2**. L'ultima frase tra virgolette mettila in corsivo e grassetto.)*

---
---

## SEZIONE 4 — 3 Recensioni (Limbico)

**Obiettivo psicologico:** Limbico puro — emozione, identificazione, sollievo. Non prove logiche: storie vere di persone reali.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-recensioni-mid mf-animate`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota
2. Aggiungi la classe `mf-recensioni-mid mf-animate`
3. Inserisci un blocco **Testo** per il titolo
4. Aggiungi **3 blocchi Immagine** in fila (layout a 3 colonne)
5. Per ogni immagine, carica lo **screenshot della recensione**
6. Aggiungi la classe `mf-recensione-img` a ciascun blocco Immagine

---

**TITOLO DA COPIARE — blocco Testo:**
```
Cosa dicono le persone che hanno già fatto il percorso
```
*(Formatta come **H2**)*

---

**SPAZI SEGNAPOSTO IMMAGINI:**

| Blocco | Cosa caricare |
|--------|---------------|
| Immagine 1 | Screenshot recensione di Alexa — *"Sono sempre stata una con le mani bucate. Ora faccio il budget tutti i mesi, risparmio soldi che non credevo di avere. Non penso più ai giorni che mancano alla paga."* |
| Immagine 2 | Screenshot recensione di Giulia — *"Ho finito di pagare il viaggio in Giappone e contemporaneamente rifacciamo il bagno. I due desideri di un anno fa sono adesso realtà."* |
| Immagine 3 | Screenshot di una terza recensione a tua scelta |

*Classe CSS da aggiungere a ogni blocco Immagine: `mf-recensione-img`*

---
---

## SEZIONE 5 — Il Programma

**Obiettivo psicologico:** Neocorteccia — presenta il metodo in modo logico e strutturato. A questo punto il lettore vuole sapere cosa ottiene.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-programma mf-animate`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota
2. Aggiungi la classe `mf-programma mf-animate`
3. Inserisci un blocco **Testo** con il contenuto qui sotto
4. Opzione consigliata: usa un blocco **Accordion** per le 5 fasi (ogni fase = una voce dell'accordion), oppure un blocco Testo unico

---

**TESTO DA COPIARE:**

```
Cosa impari nel percorso

14 video lezioni + 4 video bonus organizzati in 5 fasi


FASE 1 — METTI LE BASI
La fondazione di tutto. Stabilisci i tuoi obiettivi di risparmio e scopri dove vanno davvero i tuoi soldi.
• Lezione 1: Stabilisci gli obiettivi di risparmio e raggiungli
• Lezione 2: Stana le spese e dividile in categorie


FASE 2 — ORGANIZZA LE SPESE
Impara a vedere le spese prima che arrivino — non dopo. Scegli il metodo cartaceo o digitale.
• Lezione 3: Organizza le spese con calendario cartaceo
• Lezione 4: Organizza le spese con calendario digitale


FASE 3 — COSTRUISCI IL TUO BUDGET
Il primo Rituale di Ricchezza. Il piano scritto prima che il mese inizi — con il file digitale che diventa tuo per sempre o con carta e penna.
• Lezione 5: Primo Rituale — Il Budget
• Lezione 6: Crea il budget con il file digitale
• Lezione 7: Crea il budget con carta e penna
• Lezione 8: Come gestire le carte di credito nel budget


FASE 4 — RISPARMIO E SERENITÀ
Traccia le spese in 15 minuti a settimana. Costruisci il risparmio per obiettivi. Ogni mese parti più avanti del precedente.
• Lezione 9: Secondo Rituale — Tracciare le spese
• Lezione 10: Il risparmio — costruire la serenità economica
• Lezione 11: Terzo Rituale — La Retrospettiva
• Lezione 12: Organizza il risparmio per obiettivi


FASE 5 — SOLDI ED EMOZIONI
Capisci i meccanismi mentali che ti fanno spendere. Il lato psicologico del denaro — perché spendi come spendi.
• Lezione 13: Riconosci i pensieri che ti fanno spendere
• Lezione 14: Il primo ricordo legato ai soldi
```

*(Formatta "Cosa impari nel percorso" come **H2**, "14 video lezioni..." come testo in evidenza, ogni "FASE X" come **H3** o testo in grassetto grande)*

---

**DOPO LE 5 FASI — aggiungi un blocco Testo separato per i Bonus:**

```
🎁 4 Video Bonus inclusi in tutte le opzioni

Bonus 1 — Fondo di Emergenza
La strategia per costruirlo passo dopo passo e dire addio all'ansia da spese impreviste.

Bonus 2 — Dove Tenere i Risparmi
Conti deposito, salvadanai digitali, strumenti giusti per obiettivi a breve termine.

Bonus 3 — Banca Non Ti Temo
Come scegliere il conto e la carta giusta per la tua situazione.

Bonus 4 — Budget delle Vacanze
3 lezioni + file dedicato per calcolare i costi di ogni vacanza senza brutte sorprese.
```

---

**CTA intermedia — aggiungi un blocco Bottone:**
- Testo: `Voglio il percorso completo →`
- Link: `https://esmerise.com/maleducatifinanziari/register?p=8274`
- Classe CSS: `mf-btn`

---
---

## SEZIONE 6 — Pricing

**Obiettivo psicologico:** Neocorteccia — confronto razionale delle opzioni. La card Premium deve emergere visivamente.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-pricing`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota con classe `mf-pricing`
2. Inserisci un blocco **Testo** per il titolo e sottotitolo
3. Inserisci un blocco **Codice** (Code Block) e incolla l'HTML delle 3 card qui sotto

---

**TITOLO DA COPIARE — blocco Testo:**
```
Scegli il percorso giusto per te

Iscrizioni aperte fino al 12 aprile alle 23:59
```
*(Prima riga: **H2**. Seconda riga: testo normale in colore azzurro)*

---

**HTML DA COPIARE NEL CODE BLOCK:**
*(In Squarespace: aggiungi un blocco "Codice", attiva la modalità HTML, incolla questo codice)*

```html
<div class="mf-pricing-grid mf-animate-group">

  <!-- CARD PLUS -->
  <div class="mf-card-plus mf-animate-child">
    <span class="mf-card-label">PLUS</span>
    <div class="mf-card-title">Il Tuo Budget a Prova di Bomba</div>
    <p class="mf-card-target">Per chi vuole partire in autonomia con metodo e strumenti giusti</p>
    <ul class="mf-card-list">
      <li>14 video lezioni</li>
      <li>File Budget e Traccia Spese</li>
      <li>File obiettivi di risparmio e salvadanai digitali</li>
      <li>Fogli di lavoro stampabili</li>
      <li>Strategia anti-acquisti impulsivi</li>
      <li>4 Video Bonus inclusi</li>
      <li>Assistenza email 3 mesi</li>
    </ul>
    <div class="mf-price-old">287&euro;</div>
    <div class="mf-price">187&euro;</div>
    <div class="mf-price-rate">Oppure 3 rate da 62,33&euro; &mdash; meno di 2&euro; al giorno</div>
    <a href="https://esmerise.com/maleducatifinanziari/register?p=6185" class="mf-btn">Inizia con Plus &rarr;</a>
  </div>

  <!-- CARD PREMIUM — in evidenza -->
  <div class="mf-card-premium mf-animate-child">
    <span class="mf-card-label">PREMIUM</span>
    <div class="mf-card-title">Il Tuo Budget a Prova di Bomba</div>
    <p class="mf-card-target">La scelta pi&ugrave; equilibrata tra autonomia e affiancamento</p>
    <ul class="mf-card-list">
      <li>2 incontri personalizzati di 1 ora con noi (online)</li>
      <li>14 video lezioni</li>
      <li>File Budget e Traccia Spese personalizzato</li>
      <li>File obiettivi e salvadanai personalizzati</li>
      <li>Fogli di lavoro stampabili</li>
      <li>Strategia anti-acquisti impulsivi</li>
      <li>4 Video Bonus inclusi</li>
      <li>Assistenza WhatsApp + email 6 mesi</li>
    </ul>
    <div class="mf-price-old">497&euro;</div>
    <div class="mf-price">337&euro;</div>
    <div class="mf-price-rate">Oppure 3 rate da 112,33&euro; &mdash; meno di 4&euro; al giorno</div>
    <a href="https://esmerise.com/maleducatifinanziari/register?p=8274" class="mf-btn">Scegli Premium &rarr;</a>
  </div>

  <!-- CARD EXCLUSIVE -->
  <div class="mf-card-exclusive mf-animate-child">
    <span class="mf-card-label">EXCLUSIVE</span>
    <div class="mf-card-title">Il Tuo Budget a Prova di Bomba</div>
    <p class="mf-card-target">Per chi vuole il nostro affiancamento in ogni singola fase</p>
    <ul class="mf-card-list">
      <li>6 incontri personalizzati di 1 ora con noi (online)</li>
      <li>14 video lezioni</li>
      <li>File Budget e Traccia Spese personalizzato</li>
      <li>File obiettivi e salvadanai personalizzati</li>
      <li>Fogli di lavoro stampabili</li>
      <li>Strategia anti-acquisti impulsivi</li>
      <li>4 Video Bonus inclusi</li>
      <li>Assistenza WhatsApp + email 12 mesi</li>
    </ul>
    <div class="mf-price-old">1.297&euro;</div>
    <div class="mf-price">947&euro;</div>
    <div class="mf-price-rate">Oppure 3 rate da 315,66&euro; &mdash; 10,5&euro; al giorno</div>
    <a href="https://esmerise.com/maleducatifinanziari/register?p=8275" class="mf-btn">Prenota Exclusive &rarr;</a>
  </div>

</div>
```

---
---

## SEZIONE 7 — Chi Siamo

**Obiettivo psicologico:** Rinforzo della fiducia — credenziali + umanità. Non curriculum, ma storia vera.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-chisiamo mf-animate`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota
2. Aggiungi la classe `mf-chisiamo mf-animate`
3. Crea un layout a 2 colonne: a sinistra il **testo**, a destra la **vostra foto**
4. Aggiungi un blocco **Testo** e un blocco **Immagine**
5. Al blocco Immagine aggiungi la classe `mf-foto-autori`

---

**TESTO DA COPIARE:**

```
Chi siamo

Siamo Dora e Davide, educatori finanziari certificati AIEF e autori del libro "Maleducati Finanziari".

Dieci anni fa eravamo esattamente dove sei tu ora — senza risparmi, senza metodo, senza sistema. Ogni mese era una battaglia che non riuscivamo a vincere.

Abbiamo studiato, sperimentato, sbagliato. E costruito qualcosa che funzionasse davvero nella vita reale — non sui libri di testo.

Poi abbiamo deciso di insegnarlo.

Oggi migliaia di persone hanno già usato questo sistema per costruire la loro serenità economica. Siamo qui per fare lo stesso con te.
```

*(Formatta "Chi siamo" come **H2**)*

---
---

## SEZIONE 8 — Urgenza Finale

**Obiettivo psicologico:** Rettiliano + urgenza reale — il countdown rende la scadenza concreta e impellente.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-urgenza-finale`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota
2. Aggiungi la classe `mf-urgenza-finale`
3. Inserisci un blocco **Codice** (Code Block) e incolla l'HTML qui sotto

---

**HTML DA COPIARE NEL CODE BLOCK:**

```html
<div style="text-align:center; max-width:720px; margin:0 auto;">

  <h2 style="font-family:'Antonio',sans-serif; font-size:clamp(30px,5vw,56px); font-weight:700; color:#ffffff; line-height:1.08; margin-bottom:24px;">
    Le iscrizioni chiudono domenica 12 aprile alle 23:59
  </h2>

  <div class="mf-countdown" style="font-size:36px; justify-content:center; display:flex; gap:12px; flex-wrap:wrap; margin:28px auto; color:#ffffff;"></div>

  <p style="font-family:'DM Sans',sans-serif; font-size:17px; color:#a9cee8; max-width:520px; margin:0 auto 40px; line-height:1.65;">
    Dopo quella data le iscrizioni si chiudono e non riapriremo presto.<br>
    Se stai aspettando il momento giusto, <strong style="color:#ffffff;">questo è il momento giusto.</strong>
  </p>

  <a href="https://esmerise.com/maleducatifinanziari/register?p=8274" class="mf-btn mf-btn-large">
    Iscriviti adesso &rarr;
  </a>

</div>
```

---
---

## SEZIONE 9 — 9 Recensioni in Griglia

**Obiettivo psicologico:** Prova sociale massiva — 9 screenshot di persone reali eliminano le ultime obiezioni.

---

**Blocco Squarespace:** Nuova **Sezione vuota**

**Classe CSS da aggiungere alla SEZIONE:** `mf-recensioni-finali mf-animate`

---

**Istruzioni:**
1. Aggiungi una nuova sezione vuota
2. Aggiungi la classe `mf-recensioni-finali mf-animate`
3. Inserisci un blocco **Testo** per il titolo
4. Opzione A (consigliata): usa un blocco **Galleria** con layout a griglia, 3 colonne, e carica 9 immagini
5. Opzione B: inserisci 9 blocchi **Immagine** disposti in griglia 3x3
6. Aggiungi la classe `mf-recensione-img` a ogni immagine

---

**TITOLO DA COPIARE:**
```
Quello che dicono le persone che hanno già fatto il percorso
```
*(Formatta come **H2**)*

---

**SPAZI SEGNAPOSTO — 9 immagini da caricare:**

```
Riga 1:  [Screenshot 1]  |  [Screenshot 2]  |  [Screenshot 3]
Riga 2:  [Screenshot 4]  |  [Screenshot 5]  |  [Screenshot 6]
Riga 3:  [Screenshot 7]  |  [Screenshot 8]  |  [Screenshot 9]
```

*Carica gli screenshot delle recensioni come immagini. Classe CSS su ogni immagine: `mf-recensione-img`*

**Se usi il blocco Galleria:**
- Layout: Griglia
- Colonne: 3
- Aggiungi la classe `mf-recensioni-grid` al blocco Galleria

---
---

## SEZIONE 10 — CTA Finale

**Obiettivo psicologico:** Chiusura — ultima spinta con urgenza. 3 opzioni chiare, quella centrale (Premium) è quella da spingere.

---

**Blocco Squarespace:** Nuova **Sezione vuota** (ultima della pagina)

**Classe CSS da aggiungere alla SEZIONE:** `mf-cta-finale`

---

**Istruzioni:**
1. Aggiungi la classe `mf-cta-finale` alla sezione
2. Inserisci un blocco **Testo** per titolo e sottotitolo
3. Inserisci un blocco **Codice** con l'HTML dei 3 bottoni qui sotto

---

**TESTO DA COPIARE — blocco Testo:**
```
Inizia oggi a costruire la tua sicurezza economica.

Chiude domenica 12 aprile alle 23:59. Poi si chiude.
```
*(Prima riga: **H2**. Seconda riga: paragrafo normale)*

---

**HTML DA COPIARE NEL CODE BLOCK — 3 bottoni:**

```html
<div class="mf-cta-buttons">
  <a href="https://esmerise.com/maleducatifinanziari/register?p=6185"
     class="mf-btn-secondary">
    Plus &mdash; 187&euro;
  </a>
  <a href="https://esmerise.com/maleducatifinanziari/register?p=8274"
     class="mf-btn mf-btn-large">
    Premium &mdash; 337&euro; &nbsp;&#11088;
  </a>
  <a href="https://esmerise.com/maleducatifinanziari/register?p=8275"
     class="mf-btn-secondary">
    Exclusive &mdash; 947&euro;
  </a>
</div>
```

---
---
---

## COME PUBBLICARE — Passaggi nell'ordine corretto

Segui questi passaggi **nell'ordine esatto**. Non saltarne nessuno.

---

### PASSO 1 — Incolla il codice Header

1. Vai su **Settings** (Impostazioni) nel menu di Squarespace
2. Clicca su **Advanced** (Avanzate)
3. Clicca su **Code Injection**
4. Nel campo **HEADER** incolla **tutto il contenuto** del file `header-injection.html`
5. Clicca **Save** (Salva)

> Questo installa: i font Antonio e DM Sans, le animazioni GSAP, il countdown e la barra di urgenza in cima alla pagina.

---

### PASSO 2 — Incolla il CSS personalizzato

1. Vai su **Design** nel menu di Squarespace
2. Clicca su **Custom CSS**
3. Incolla **tutto il contenuto** del file `custom.css`
4. Clicca **Save**

> Questo attiva tutti gli stili: colori, tipografia, card pricing, griglia recensioni, animazioni.

---

### PASSO 3 — Crea la pagina di lancio

1. Vai su **Pages** (Pagine)
2. Clicca **+** per creare una nuova pagina
3. Scegli una pagina **vuota** (non un template con contenuti predefiniti)
4. Dai alla pagina un nome interno tipo "Landing Lancio Aprile 2026"
5. Assicurati che la pagina **non sia nel menu di navigazione** (nelle impostazioni pagina disattiva "Navigation")

---

### PASSO 4 — Costruisci le sezioni nell'ordine

Costruisci le sezioni nell'ordine esatto indicato in questo documento:

| N. | Sezione | Note |
|----|---------|------|
| 0 | Urgency Bar | Automatica — nessuna azione richiesta |
| 1 | Hero | Prima sezione della pagina |
| 2 | Problema | Sezione vuota, sfondo bianco |
| 3 | Storia | Sezione vuota, sfondo blu chiaro (il CSS lo imposta) |
| 4 | 3 Recensioni | Sezione vuota, sfondo navy (il CSS lo imposta) |
| 5 | Programma | Sezione vuota, sfondo bianco |
| 6 | Pricing | Sezione vuota, contiene Code Block |
| 7 | Chi Siamo | Sezione vuota, sfondo blu chiaro |
| 8 | Urgenza Finale | Sezione vuota, contiene Code Block |
| 9 | 9 Recensioni | Sezione vuota, sfondo bianco |
| 10 | CTA Finale | Sezione vuota, ultima della pagina |

---

### PASSO 5 — Aggiungi le classi CSS alle sezioni

Per ogni sezione, aggiungi la classe CSS indicata (vedi le istruzioni all'inizio di questo documento e la tabella qui sotto):

| Sezione | Classe CSS da aggiungere |
|---------|--------------------------|
| Hero | `mf-hero` |
| Problema | `mf-problema mf-animate` |
| Storia | `mf-storia mf-animate` |
| 3 Recensioni | `mf-recensioni-mid mf-animate` |
| Programma | `mf-programma mf-animate` |
| Pricing | `mf-pricing` |
| Chi Siamo | `mf-chisiamo mf-animate` |
| Urgenza Finale | `mf-urgenza-finale` |
| 9 Recensioni | `mf-recensioni-finali mf-animate` |
| CTA Finale | `mf-cta-finale` |

---

### PASSO 6 — Carica le immagini delle recensioni

1. Nella Sezione 4 (3 recensioni): carica i 3 screenshot come blocchi Immagine
2. Nella Sezione 9 (9 recensioni): carica i 9 screenshot
3. Ricordati di aggiungere la classe `mf-recensione-img` a **ogni** blocco immagine delle recensioni
4. Nella Sezione 7 (Chi Siamo): carica la vostra foto e aggiungi la classe `mf-foto-autori`

---

### PASSO 7 — Verifica finale prima di pubblicare

Controlla questi punti:

- [ ] La barra di urgenza con countdown appare in cima alla pagina
- [ ] I font sono Antonio (titoli) e DM Sans (testo)
- [ ] Lo sfondo Hero è blu navy con gradiente
- [ ] La card Premium nel pricing è più grande e ha il badge "Più scelta"
- [ ] Tutti i link dei bottoni portano all'URL corretto
- [ ] La pagina è responsive su mobile (usa l'anteprima mobile di Squarespace)
- [ ] Il countdown mostra i giorni/ore/minuti/secondi mancanti al 12 aprile
- [ ] Le animazioni scroll si attivano quando scorri la pagina

---

### PASSO 8 — Pubblica la pagina

1. Clicca **Save** in alto a destra nell'editor
2. Clicca **Publish** (o disattiva il lock "Not linked" della pagina)
3. Condividi il link della pagina nella newsletter e sui social

---

> **Problema tecnico?**
> Se qualcosa non si vede correttamente:
> 1. Verifica che il CSS sia stato salvato correttamente in Design > Custom CSS
> 2. Verifica che l'header injection sia stata salvata in Settings > Advanced > Code Injection > Header
> 3. Prova a svuotare la cache del browser (Ctrl+Shift+R su Windows)
> 4. Prova in una finestra in incognito per vedere la pagina come la vede un visitatore
