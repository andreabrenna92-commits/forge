# FORGE — Diet & Training

Single Page App (HTML/CSS/JS nativo, zero build) per gestire piano alimentare e allenamento.
Dark mode, mobile-first, installabile come PWA su iPhone, funziona offline.

## Funzioni
- **Oggi** — dashboard con macro del giorno, pasti spuntabili, allenamento.
- **Cibo** — pasti del giorno con bottone *Sostituisci* (alternative iso-macro).
- **Workout** — schede A/B/C/D con RPE, doppia progressione, timer di recupero, log carichi.
  Selettore *Allenamento del giorno* per assegnare qualsiasi scheda a qualsiasi data.
- **Progressi** — peso corporeo con grafico + storico carichi.
- Persistenza in `localStorage`.

## Uso locale
Apri `index.html` nel browser. Per installazione/offline serve un host HTTPS (vedi sotto).

## Installazione su iPhone
1. Apri l'URL (GitHub Pages) in **Safari**.
2. Condividi → **Aggiungi a Home**.

## File
- `index.html` — app completa
- `manifest.webmanifest`, `sw.js` — PWA + offline
- `icon-*.png` — icone app
