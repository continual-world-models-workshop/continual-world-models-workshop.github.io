# Continual World Models | NeurIPS 2026 Workshop

This repository contains only the current static GitHub Pages deployment.

## Layout

| Path | Purpose |
| --- | --- |
| `index.html` | GitHub Pages entry point |
| `assets/` | Current Vite JavaScript and stylesheet bundles |
| `media/` | Current workshop images and portraits |
| `2026/` | Durable, self-contained NeurIPS 2026 workshop archive |

The maintained React source is organized separately in the workshop project under `client/src/features/workshop/`.

## Edition URLs

The repository root always serves the latest workshop edition. Each deployment
also publishes the active edition under its year, for example `/2026/`.
When the 2027 edition is ready, set `WORKSHOP_ARCHIVE_YEAR=2027` for the
export. The export preserves the existing `2026/` archive while updating the
root to the latest edition.
