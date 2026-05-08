# Changelog

## 2026-05-08 — v1.0 (Direction C, Editorial)

- Replaced `index.html` with the v1.0 Editorial mockup (Direction C, selected
  2026-05-07).
- Resolved PRD §13 must/should items inline:
  - Promoted `ENCLAVE` foundation mark to `<h1>` (single h1 per page).
  - Added skip-to-content link (`<a href="#main" class="vc-skip">`) and `<main>` wrapper.
  - Wired `og:image`, `og:image:alt`, `twitter:image`, `<link rel="canonical">`.
  - Added favicon link block (`favicon.ico`, `favicon-32.png`, `apple-touch-icon.png`).
  - Added inline `<section id="join">` Coalition apply CTA above the footer (resolves the
    `#join` anchor, links to `https://e5enclave.com/coalition/apply/` and `mailto:contact@e5enclave.com`).
- Removed the duplicate `static.yml` workflow; `deploy-pages.yml` is now the
  canonical GitHub Pages deploy.
- Brand assets (`favicon.ico`, `assets/favicon-32.png`, `assets/apple-touch-icon.png`,
  `assets/og.png` — 1200×630 export of the crest + foundation slab) live in
  `assets/`. See `assets/README.md` for source-of-truth pointers to the
  canonical brand assets in `iamgodiam/e5-website`.

## 2026-05-05

- Created repository for E5 Enclave editorial homepage.
- Added static `index.html` page.
- Added README and agent handoff rules.
- Added GitHub Pages deployment workflow.
