# Glyph Harbor — Hub Landing Page

Static landing page for `glyphharbor.com` apex. Cloudflare Workers Assets deploy.

Type-led, Blue Astrolabe palette, no logo dependency for v0. Designed per Mira's brief 2026-05-14:
`shared/business-launches/incubator/cycles/mira-glyph-harbor-hub-landing-page-brief-2026-05-14.md`

## Structure

- `public/index.html` — page markup
- `public/styles.css` — Blue Astrolabe palette + layout
- `wrangler.toml` — Cloudflare Workers Assets config (serves `public/`)

## Deploy

Push to `main` → Cloudflare Workers auto-deploys (same pattern as `prompt-diff-guard` worker).

## Brand

Glyph Harbor is an operating brand of Lawrence Holl, a Connecticut sole proprietor.
