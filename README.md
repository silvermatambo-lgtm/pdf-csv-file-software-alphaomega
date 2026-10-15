# Alpha and Omega Advisors PDF Editor

Professional PDF Editor & PDF-to-CSV Converter web application for **Alpha and Omega Advisors** – Professional Accountants and Tax Advisors.

![Logo](public/logo.jpg)

## Features

- **PDF Viewer** – Upload and view multi-page PDFs with zoom and page navigation
- **Text Annotations** – Add text notes anywhere on a page
- **Download Edited PDF** – Export the PDF with your annotations embedded
- **PDF → CSV Conversion** – Extract text content (grouped into rows) and download as CSV
- **100% Client-side** – Your files never leave the browser
- Clean branded UI using the official Alpha and Omega Advisors logo

## Tech Stack

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- pdf.js (viewing & text extraction)
- pdf-lib (editing / writing annotations)
- PapaParse (CSV generation)
- Lucide React (icons)

## Deploy to Vercel (recommended)

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import the GitHub repository
4. Leave all defaults (Next.js is auto-detected)
5. Click **Deploy**

Your app will be live in under a minute.

## Local Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
alpha-omega-pdf-editor/
├── public/
│   └── logo.jpg              # Official logo
├── src/
│   └── app/
│       ├── globals.css
│       ├── layout.tsx
│       └── page.tsx          # Main application
├── package.json
├── next.config.mjs
├── tailwind.config.ts
└── README.md
```

## Notes

- Processing is entirely client-side for privacy and simplicity.
- Text extraction quality depends on the PDF (scanned image-only PDFs will have limited text).
- For best results use text-based (not scanned) PDFs.

---

© Alpha and Omega Advisors – Professional Accountants and Tax Advisors
