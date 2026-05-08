# Brand assets

This directory holds binary brand assets for the editorial homepage. The
canonical source-of-truth for E5 Enclave brand assets lives in the sister
repo: `iamgodiam/e5-website` under `src/assets/img/brand/`.

The homepage repo ships *copies* (not symlinks — GitHub Pages does not
follow symlinks reliably). When a brand asset changes in `e5-website`, sync
the corresponding file here in the same PR pair.

## Files referenced from `index.html`

| Path | Purpose | Status |
|---|---|---|
| `/favicon.ico` (root) | Default favicon | needs export |
| `/assets/favicon-32.png` | 32×32 PNG favicon | needs export |
| `/assets/apple-touch-icon.png` | 180×180 iOS touch icon | needs export |
| `/assets/og.png` | 1200×630 social card (crest + foundation slab) | needs export |

## How to generate

The mockup ships an inline SVG crest (lines ~580-595 of `index.html`) and
the foundation slab as styled HTML. To produce `og.png`:

1. Open `index.html` in a headless browser at 1200×630.
2. Crop to the masthead + foundation slab.
3. Export as PNG at 100% quality.
4. Drop into `assets/og.png`.

Tools that work: Puppeteer, Playwright, or Figma if the SVG is imported.

The favicon set is the E5 mark from the foundation slab (the italic `5`
inside `E`). Export as 16×16, 32×32, and 180×180 (apple-touch).
