# عبقري — Landing Page

A responsive RTL landing page using the official uploaded logo assets and an original looping background video. Light "paper" institutional theme with dark hero/CTA bands, scroll reveal animations, a hamburger menu, full mobile layouts, `prefers-reduced-motion` support (CSS + JS), and no-JS-safe reveal animations. No CDN dependencies — all JavaScript is inline and dependency-free.

## Run
Use a local HTTP server (recommended for fonts and the background video):

```bash
python -m http.server 8080 --directory abqari_landing_page
```

Open `http://localhost:8080`.

## Production checklist
- Replace the hand-crafted prototype mockups (`assets/dashboard-mock.svg`, `assets/mobile-mock.svg`) with real product screenshots once available — the page labels them honestly as early-stage previews.
- Replace the `#lang` toast placeholder with a real bilingual switch once approved English copy exists.
- Make `og:image` / `twitter:image` absolute URLs (`https://YOUR-DOMAIN/assets/...`) at deploy time.
- Confirm the final legal/privacy links.
- Verify the indicative simulation figures before public use.
- Contact: `support@3bqary.com` — Madinaty, Cairo, Egypt (already wired into the CTA and footer; update if it changes).

## Brand assets
The two uploaded images are preserved unchanged under `assets/*-official.jpg`; optimized WebP copies are used by the page.
