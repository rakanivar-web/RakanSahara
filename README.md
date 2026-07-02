# Sahara Arena

Sahara Arena — Kuwait's premier entertainment destination. Built with React +
[@wix/design-system](https://www.npmjs.com/package/@wix/design-system) and the
Sahara Arena brand system (ITC Avant Garde Gothic + Palestine fonts, terracotta /
sage / beige palette, geometric motif set).

This repository hosts the static production builds:

- **`/` (index.html)** — the responsive marketing website (top nav, hero, event
  grid, venues, interactive masterplan, footer).
- **`/app/`** — the phone-framed mobile app UI (bottom tab bar: Home · Events ·
  Venues · Explore · Profile).

## GitHub Pages

Enable Pages → **Deploy from a branch** → `main` / root. The site will be at:

- `https://rakanivar-web.github.io/RakanSahara/`
- `https://rakanivar-web.github.io/RakanSahara/app/`

Asset paths are relative, so it also works from any static host or subpath.
`.nojekyll` is included so Pages serves all files as-is.

## Content

Static demo — all events/venues/profile are mock data; ticketing, auth, and CMS
are not wired up. Source projects live in the `Sahara Arena Website` workspace
(`WDS Web App` and `WDS Mobile App`).
