# E5 Enclave Editorial Homepage

A single-page editorial homepage for **E5 Enclave Incorporated — A Lineage-based Think Tank**.

This repo holds the canonical, frozen v1.0 founding artifact: a polished
masthead-style landing page deployed to GitHub Pages. Anything beyond this
single page (Doctrine, Pillars detail pages, The Record, programs, blog,
donate, store, FAQ, legal) lives in the sister repo
[`iamgodiam/e5-website`](https://github.com/iamgodiam/e5-website), which is the
full multi-page operational website.

## Files

- `index.html` — the static editorial homepage (v1.0 · Direction C).
- `assets/` — brand assets: favicons, og.png. See `assets/README.md`.
- `AGENTS.md` — agent handoff and editing rules.
- `CHANGELOG.md` — change history.
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment workflow.
- `package.json` — lightweight local preview commands.

## Local preview

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages deployment

1. **Settings → Pages → Build and deployment → GitHub Actions**.
2. Push to `main`.
3. The workflow at `.github/workflows/deploy-pages.yml` publishes the site.

## Canonical content anchors

- E5 Enclave Incorporated · 501(c)(3) · EIN 99-3822441
- Founded Juneteenth · MMXXVI · Liberty City, Florida
- A Lineage-based Think Tank · comprised of a Coalition of the Willing
- The Five Pillars: Environmental · Economic · Educational · Engagement · Emancipated
- Restitution 246 — campaign under Emancipated
- The Record (founding documents): Parallel Negros · Measure the Wound · Restitution 246
- Closing cadence: "For the next thousand years."

## Relationship to `e5-website`

| Concern | Repo |
|---|---|
| Single-page editorial artifact (homepage of record) | **this repo** |
| Multi-page operational site (doctrine, pillars, record, programs, coalition, apply, press, contact, blog, donate, store, faq, legal) | `iamgodiam/e5-website` |
| Canonical CSS / brand assets | `iamgodiam/e5-website` (`src/assets/css/editorial.css`, `src/assets/img/brand/`) |
| Production domain | `e5enclave.com` (lives in `e5-website`'s Azure SWA deploy) |

This repo's `index.html` carries an inline `<style>` block per the v1.0
"single self-contained file, no build step" mandate. When the canonical CSS
in `e5-website` changes, hand-sync the inline block here.
