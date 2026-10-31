# Bangla QR 249

Bangla QR 249 is a mobile-first QR generator Progressive Web App.

**Live app:** https://banglaqr249.vercel.app/

## Project files
- `index.html` — application interface
- `manifest.webmanifest` — PWA metadata and app icons
- `sw.js` — service worker and offline app-shell caching
- `logo.svg` — Bangla QR brand logo
- `qrcode.js` — bundled QR generation library (when present in the deployed build)

## PWA
Serve the project from HTTPS or localhost. Open the site once while online so the service worker can cache the app shell, then install it from the browser menu.

## Payment safety
Generating a QR code does not confirm that a payment was made. Verify payment in the receiving account or official merchant app.