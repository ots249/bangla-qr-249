# Bangla QR 249

Offline-capable Progressive Web App QR generator.

**Live app:** https://banglaqr249.vercel.app/

## Features
- QR generation is performed locally in the browser.
- PWA manifest and service worker cache the application shell for offline use after the first online visit.
- Mobile-first responsive interface.

## Project files
- `index.html` — app interface and QR payload logic
- `qrcode.js` — bundled QR generator library
- `manifest.webmanifest` — PWA metadata
- `sw.js` — offline cache/service worker
- `logo.svg` — Bangla QR logo
- `qrcode-generator.LICENSE` — QR library license

## Local development
Serve over HTTPS or localhost. Service workers require a secure context.

## Payment safety
QR generation does not confirm payment or guarantee settlement. Verify every payment in the receiving account or official merchant app.
