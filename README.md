# FITNOMAD — Smart Diet & Training

Single Page App (HTML/CSS/JS nativo, zero build) per gestire piano alimentare e allenamento.
Dark mode premium, mobile-first, installabile come PWA su iPhone, funziona offline.

## Funzioni
- **Onboarding obiettivo** — Massa / Definizione / Ricomposizione: adatta macro e strategia di allenamento.
- **Oggi** — dashboard con macro del giorno (adattati all'obiettivo), pasti spuntabili, allenamento.
- **Cibo** — pasti del giorno con bottone *Sostituisci* (alternative iso-macro). [PRO]
- **Workout** — schede A/B/C/D con RPE, doppia progressione, timer di recupero, log carichi,
  selettore *Allenamento del giorno* e *Attrezzatura* (Casa/Manubri/Palestra).
- **Diario alimentare** — modifica i grammi di ogni ingrediente, deseleziona ciò che non hai mangiato,
  aggiungi alimenti extra dal database; totali Calorie/Proteine/Carboidrati/Grassi (Assunti vs Obiettivo) in tempo reale.
- **Stats** — peso corporeo con grafico + storico carichi. [PRO]
- **Profilo** — abbonamento (Trial 7gg / PRO), obiettivo, promemoria notifiche.
- **Promemoria** — notifiche browser + toast in-app per pasti e allenamento.
- **Monetizzazione** — Trial 7 giorni → paywall PRO (pronto per Stripe/PayPal).
- Persistenza completa in `localStorage`.

## Uso locale
Apri `index.html` nel browser. Per installazione/offline serve un host HTTPS (vedi sotto).

## Installazione su iPhone
1. Apri l'URL (GitHub Pages) in **Safari**.
2. Condividi → **Aggiungi a Home**.

## File
- `index.html` — app completa
- `manifest.webmanifest`, `sw.js` — PWA + offline
- `icon-*.png` — icone app
