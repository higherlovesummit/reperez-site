# reperez.com

Static landing page for Re Perez. Hosted on Cloudflare Workers & Pages (project **reperez**, account "Category of One Branding"), deployed automatically from this repo's `main` branch.

## How to update
Tell Claude what to change. Claude edits `index.html`, commits, and pushes to `main`. Cloudflare rebuilds and the change is live in ~30 seconds. Nothing to upload by hand.

## Files
- `index.html` — the whole site (single page).
- `assets/reperez-logo-gold-white.png` — logo (never retypeset as text).
- `assets/og-image.png` — 1200×630 social share image.

## Brand system
Background #000 · gold #D8B478 · sand #CFC6BA · hairline rgba(216,180,120,0.28).
Fonts: Cormorant Garamond 600 (display), EB Garamond (body/italic quotes), Raleway uppercase tracked (labels/buttons). Body copy white; italic accents gold/sand.

## Analytics
Google Analytics G-1Q30BKSW9K — must stay in `<head>`.

## Cloudflare settings
Build command: none · Build output directory: `/` · Production branch: `main`.
