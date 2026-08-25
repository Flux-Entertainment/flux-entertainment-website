# Flux Entertainment — Astro Project

## Structure
- `src/layouts/Layout.astro` — shared header, footer, nav, global styles (used by every page)
- `src/pages/*.astro` — the 9 pages (Home, About, Contact, + 6 service pages)
- `public/images/` — every photo/logo, extracted from the old base64-embedded HTML into real files

## Videos
All 15 videos are hosted on Cloudflare R2, served via videos.fluxentertainment.com.au
Every <source> tag in the pages already points there directly — nothing to configure.

## To run locally / deploy
npm install
npm run dev      # local preview
npm run build    # production build, outputs to dist/
