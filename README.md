# Infinity Offer Builder (web app)

Konica Minolta technical & financial offers for Infinity Distribution, in the browser.
Drop a Foliant PDF, fill in the client and prices, and download the Word offer.

- Live: https://ahmedsalah-93.github.io/Offer-Builder/
- `data/library.json`: machines, consumables, company details and defaults, exported from the Offer Builder in claude.ai.
- `assets/`: header, logo, part pictures and the Noto Kufi Arabic fonts used in the offer.
- `vendor/`: pdf.js 3.11.174, docx 9.5.1, JSZip 3.10.1.
- `config.js`: `OFFER_LOG_URL`, the Google Apps Script address that records each offer in the log sheet.
