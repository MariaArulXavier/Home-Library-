HOME LIBRARY — PREMIUM EDITION
================================
Bilingual English/Tamil offline-first personal library manager.

QUICK START (simplest)
1. Extract this ZIP to a folder on your computer.
2. Open index.html in a modern browser (Chrome, Edge, Firefox).
3. Start adding books. Records are saved in that browser's IndexedDB on this computer.
No server, PHP, MySQL, account, or internet connection is required for normal use.

OPTIONAL PWA / INSTALLABLE MODE
Service worker caching and PWA installation require localhost or HTTPS.
If Python is installed, open a terminal in this folder and run:
  python -m http.server 8000
Then visit http://localhost:8000 in your browser and use the browser's Install app option.
The website itself still works offline after the first load in this mode.

FEATURES
- Dashboard, book catalogue, search and filters
- Large-collection friendly IndexedDB storage
- Visual bookshelf / grid catalogue view with saved cover images (images resized and compressed locally)
- ISBN / barcode camera scanning where supported by the browser; manual ISBN entry always available
- Book metadata: ISBN, author, publisher, year, edition, language, category,
  copies, shelf/rack, reading status, pages/progress, purchase details, condition, notes
- Custom categories
- Reading desk and progress summaries
- Lending register, due dates, overdue indicator, return tracking
- Reports and print view
- Full JSON backup and restore
- CSV catalogue export
- English/Tamil language selector (interface)
- Responsive desktop/tablet/mobile layout
- No backend or external runtime dependencies

IMPORTANT DATA / PRIVACY NOTES
- Data is stored in the browser profile on this device. It is not automatically
  shared or synced with another browser, computer, or phone.
- Do not clear browser site data unless you have a backup.
- Use Backup & Restore regularly. Keep backup files on another drive/cloud location.
- Browser storage can be cleared by browser cleanup tools or by resetting the profile.
- This is a personal single-user tool, not a multi-user hosted system.
- Barcode camera scanning depends on browser BarcodeDetector support and camera permission; use HTTPS or localhost. Manual ISBN entry is available everywhere.
- Automatic ISBN metadata lookup, OCR, and cloud sync are intentionally not included because the core application is offline-first.
