# StackPDF — Compress PDF Files

A free, **100% client-side** PDF compression tool that runs entirely in your browser. Drop a PDF file, pick a compression level, and download a smaller PDF — no uploads, no servers, no sign-up, your documents never leave your device.

## Features

- **Client-side PDF compression** — files are processed locally with [pdf-lib](https://pdf-lib.js.org/) running in the browser
- **Drag-and-drop upload** — drop a PDF or click to browse
- **Compression levels** — choose how aggressively to shrink the file
- **Live size comparison** — see original vs. compressed size before downloading
- **One-click download** — save the compressed PDF instantly
- **Privacy-first** — zero network calls for processing; nothing is uploaded anywhere

## Tech stack

- **HTML5** — single-page structure (`index.html`)
- **CSS** — Tailwind CSS via CDN + custom styles, Inter font
- **JavaScript (vanilla)** — `pdf-lib` from CDN for PDF manipulation

No build step, no dependencies to install.

## Quick start

Open `index.html` in any modern browser — that's it.

```bash
# or serve locally (optional, for consistent CDN behavior)
npx serve .
```

1. Drop a PDF file onto the page (or click to browse).
2. Choose a compression level.
3. Download the compressed PDF.

## Project structure

```
.
├── index.html     # Entire app — UI, styles, and JS in one file
└── README.md
```

## Deploy notes

This is a pure static single-page app. Deploy anywhere static sites run (GitHub Pages, Cloudflare Pages, Netlify) — no build step required.

Built by Girish Lade — [ladestack.in](https://ladestack.in)
