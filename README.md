# Barcode Check PWA

Offline-capable barcode verification PWA (single-file app + service worker).

- Camera-based 1D barcode scanning (Code128 / Code39 / EAN / ITF / Codabar / UPC) via html5-qrcode.
- The embedded code library is AES-GCM encrypted (PBKDF2 key derivation); the site is public, the data is not.
- Load once, then works fully offline (service worker). Scan log persists in localStorage; CSV export for records and remaining-items checklist.

Built from an Excel source; redeploy by replacing index.html.
