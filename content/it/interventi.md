---
title: "Interventi — Redesign del Sito Web"
description: "Documentazione degli interventi effettuati nel redesign del sito web di Marina di Conca Verde: dalla versione precedente alla versione attuale."
translations:
  it: "/interventi"
  en: "/interventions"
  de: "/interventionen"
  fr: "/interventions"
hero:
  eyebrow: "Progetto · Redesign"
  title: "Interventi"
  subtitle: "Tutto quello che è stato fatto per portare il sito dalla versione precedente a quella attuale."
  image: ""
  imageAlt: "Redesign sito web Marina di Conca Verde"
  primaryCta:
    label: "Contatti"
    href: "/it/contatti"
  secondaryCta:
    label: "Home"
    href: "/it/"
textBlock:
  eyebrow: "Redesign"
  title: "marinadiconcaverder.it 2.0"
stats:
  - value: "2026"
    label: "Anno del redesign"
  - value: "21+"
    label: "Pagine create"
  - value: "Nuxt 3"
    label: "Nuovo framework"
  - value: "100%"
    label: "Mobile friendly"
---

**Stato attuale del progetto**

Il sito è stato rifatto **momentaneamente in una sola lingua** (italiano).  
Si tratta di una versione di transizione / restyling parziale, con l’obiettivo di migliorare l’esperienza utente, l’estetica e la fruibilità, mantenendo però gran parte della struttura informativa originale.

## Interventi principali realizzati

### 1. Header (intestazione)

Ridisegnato completamente per maggiore chiarezza e modernità.

#### 1.1 Elementi presenti nell’header

- **Banner superiore** (opzionale) con:
  - Nome della località
  - Contatti principali (telefono, email, WhatsApp…)
- **Logo** (provvisorio – da sostituire con versione definitiva)
- **Selettore lingua** (con bandiere)
  - Le bandiere degli altri linguaggi appaiono solo al **mouseover/hover** sulla bandiera della lingua corrente
- **Menu di navigazione**

#### 1.2 Menu di navigazione

- **Struttura**: ereditata dal vecchio sito (non modificata nei contenuti)
- **Comportamento differente per dispositivo**:
  - **Desktop** → menu orizzontale con sottomenù dropdown chiari
  - **Mobile** → menu hamburger con due logiche distinte:
    - Link diretti (pagine senza figli)
    - Apertura dei sottomenù (pagine con figli) → espansione accordion-style

### 2. Sezione Hero

- **Rifacimento completo** della sezione hero in homepage e nelle pagine principali
- Nuova immagine di sfondo (mista: foto originali + foto professionali da repository gratuiti)
- Testi rivisti e ottimizzati (se necessario possono essere snelliti, è solo per illustrarne le possibilità)
- Possibilità di inserire bottoni / call-to-action (prenota, scopri, contatti, ecc.)

### 3. Corpo della pagina (Body – struttura modulare)

Le pagine sono composte da **blocchi componibili** (facoltativi), disposti in ordine logico:

1. **Hero** (come descritto sopra, momentaneamente senza carosello, ma con possibilità di inserire ciascun carosello per ogni pagina)
2. **Navigazione veloce con immagini**  
   (card/griglie con foto + link rapidi alle sezioni principali)
3. **Blocco riassuntivo**
   - Numeri chiave (posti barca, appartamenti, servizi…)
   - Informazioni salienti della pagina corrente
4. **Altri blocchi** (facoltativi e personalizzabili):
   - Testi descrittivi
   - Gallery fotografiche
   - Video embed
   - Call to action

**Nota sulle immagini e contenuti**  
Tutti i contenuti visivi e testuali provengono da:

- Foto e testi del vecchio sito
- Foto professionali da repository gratuiti (Unsplash, Pexels, Freekpik)
- Immagini generate tramite AI (non attualmente presenti, possibile utilizzo per eventuali icone o illustrazioni)

### 4. Sidebar (colonna laterale – attualmente presente)

Contenuti provvisori:

- **Sezione “Il tuo soggiorno”**  
  (ancora non collegata ad API né a sistema di invio email)
- **Link alla pagina dei traghetti**  
  (iframe o redirect verso il motore di prenotazione)
- **Icone social**
- **Recensioni**
  - Integrazione widget/iframe da TripAdvisor e/o Booking.com non attualmente presente, perchè dev'essere verificata la properietà dell'account tramite i canali ufficiali del cliente.

### 5. Footer

Design semplice e pulito contenente:

- Informazioni sulla società
- Contatti (telefono, email, indirizzo)
- Link utili:
  - Privacy Policy
  - Cookie Policy
  - Condizioni di utilizzo
- Copyright
- Link a questa pagina di spiegazione degli interventi (temporaneo)

## Prossimi passi previsti

- Integrazione multilingua completa
- Logo definitivo
- Collegamento reale della sezione “Il tuo soggiorno” (form → email / API)
- Ottenimento e inserimento ufficiale dei widget recensioni (TripAdvisor / Booking)
- Eventuale sostituzione di foto stock con scatti originali della struttura
- Ottimizzazioni SEO e performance
- Test responsive su tutti i dispositivi
- Eventuale aggiunta di nuove sezioni se richieste dal cliente

**Ultimo aggiornamento:** 26 Febbraio 2026
