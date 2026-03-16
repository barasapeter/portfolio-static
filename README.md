# portfolio-static

A lightweight, static personal portfolio site built with HTML, CSS, and vanilla JavaScript.

## Overview

This repository contains a single-page portfolio website with:

- Responsive layout using Tailwind CSS (loaded from CDN)
- Dark mode support
- A terminal-style command interface in the header
- Portfolio sections (about, projects, stack, experience, contact)
- Static asset support for favicons, profile image, and manifest

## Tech stack

- **HTML5** (`index.html`)
- **CSS3** (`index.css`)
- **Vanilla JavaScript** (`index.js`)
- **Tailwind CSS CDN**
- **Lucide icons CDN**

## Project structure

```text
.
├── index.html          # Main page markup
├── index.css           # Custom styles
├── index.js            # Terminal command behavior + interactions
├── me.jpeg             # Profile image
├── site.webmanifest    # PWA manifest metadata
├── favicon* / apple-* / android-* icons
└── README.md
```

## Running locally

Because this is a static site, you can run it with any simple file server.

### Option 1: Python

```bash
python3 -m http.server 8000
```

Then open: <http://localhost:8000>

### Option 2: Node (if `serve` is installed)

```bash
npx serve .
```

## Deployment

You can deploy this site to any static hosting provider, for example:

- GitHub Pages
- Netlify
- Vercel (static output)
- Cloudflare Pages
- AWS S3 + CloudFront

## Notes

- The resume terminal command currently points to `/resume.pdf`, so include that file at the project root if you want downloads to work.
- External dependencies (Tailwind and Lucide) are loaded via CDN in `index.html`.

## License

No license is currently specified in this repository.
