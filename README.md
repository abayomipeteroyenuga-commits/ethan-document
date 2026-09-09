# Ethan Documents — Web / Index App

GitHub-ready static PWA reconstructed from the Ethan Office / Ethan Document Utility project.

## Deploy
Upload every file/folder in this ZIP to the root of your GitHub repository, then deploy with GitHub Pages, Vercel, Netlify, Cloudflare Pages or another HTTPS static host.

## Included
- index.html
- assets/style.css
- assets/app.js
- PWA manifest and service worker
- 192px / 512px app icons
- Local document editor and drafts
- File manager metadata
- PDF merge/split/watermark via pdf-lib CDN
- OCR via Tesseract.js CDN
- TXT / image to PDF via jsPDF CDN
- Signature pad
- Backup / restore

## Important
Imported file bytes are kept only for the current browser session in this static build; after a reload, re-import the original file to open/process it. Drafts and metadata are stored in localStorage. OCR/PDF helper libraries need internet the first time they are loaded from their CDNs. Real Word/Excel/PowerPoint conversion is not simulated; it requires a conversion backend or office engine.
