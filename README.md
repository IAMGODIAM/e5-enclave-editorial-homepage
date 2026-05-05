# E5 Enclave Editorial Homepage

A static editorial-style homepage for **E5 Enclave Incorporated — Coalition of the Willing**.

This repository packages a single-page HTML site using the Vogue/runway editorial visual direction while preserving the E5 Founding Framework, Juneteenth rollout, Five Pillars, Coalition model, Restitution 246 framing, and closing doctrine.

## Files

- `index.html` — the static editorial homepage.
- `AGENTS.md` — agent handoff and editing rules.
- `CHANGELOG.md` — change history.
- `.github/workflows/deploy-pages.yml` — optional GitHub Pages deployment workflow.
- `package.json` — lightweight local preview commands.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## GitHub Pages deployment

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, choose **GitHub Actions**.
3. Push to `main`.
4. The workflow in `.github/workflows/deploy-pages.yml` publishes the static site.

## Canonical content anchors

The page should remain aligned to:

- E5 Enclave Incorporated
- Coalition of the Willing
- Founding Framework & Juneteenth Rollout
- The Five Pillars: Environmental, Economic, Educational, Engagement, Emancipated
- Restitution 246 as the Emancipated campaign
- Coalition directory/backlink model
- Closing cadence: “The harm was structural. The remedy must be structural.”
