# Changelog

## 2026-05-09 — v2.0 (Editorial v2 handoff)

Replaces the v1.0 mockup with the v2 editorial homepage from the design
handoff package. Substantial direction change, not a tweak.

- **Founding date corrected.** Hero now carries the three-date hierarchy:
  Founded **2 June 2024** · Liberty City. Public Announcement Juneteenth ·
  MMXXVI. Eden Launch 17 February · MMXXVII. The v1 conflation of founding
  with Juneteenth is fixed.
- **Tagline corrected.** *A lineage-led think tank comprised of a Coalition
  of the Willing.* (was "lineage-based").
- **Magazine framing stripped.** No Volume / Number / Issue / "In this issue"
  / № / page numbers anywhere in the masthead chrome. The site is a record,
  not a newsletter.
- **Unified `E5 + ENCLAVE` wordmark.** Composed as a single optical unit
  on the foundation plinth. ENCLAVE dominant; E5 the seal that opens it.
- **Tagline as co-equal italic gold.** Reads as the line that carries what
  we are, before the wordmark resolves into meaning.
- **Two-palette toggle.** Editorial (cream/oxblood) and original (parchment/
  forest/ochre). Persists via `localStorage.e5-palette`. Discreet two-swatch
  pill in the nav. Both palettes first-class.
- **Counter band.** Three metrics under the hero — supporters of record,
  member organizations, pillars in motion. Eased count-up via
  IntersectionObserver + RAF. Tabular numerals. `prefers-reduced-motion`
  respected.
- **Coalition Covenant section.** Four terms: stake of any size, four
  convenings per year, eight hours of presence, introduce two others.
- **Concentric mesh seal motion.** Slow ring rotation (220s), counter-rotation
  (140s), 7-second breath. SVG + CSS keyframes. `prefers-reduced-motion`
  respected.
- **Print stylesheet.** Flattens dark plinth to ink-on-white for funder
  packets and archival use.
- **OG / Twitter description corrected.** Reflects the three-date hierarchy
  rather than the v1 founding-Juneteenth conflation.
- **Internal canonical Record links.** The three founding dispatches
  (Parallel Negros, Measure the Wound, Restitution 246) now link to
  `https://e5enclave.com/record/{slug}/` rather than the base44 reading
  surface. The base44 documents remain available; the internal route is
  canonical.

## 2026-05-08 — v1.1 (PRD §13 polish)

- Promoted ENCLAVE foundation mark to `<h1>` (single h1 per page).
- Added skip-to-content link and `<main id="main">` wrapper.
- Wired `og:image`, `og:image:alt`, `twitter:image`, `<link rel="canonical">`.
- Added favicon link block.
- Added inline `<section id="join">` Coalition Apply CTA above the footer.
- Removed duplicate `static.yml` workflow.

## 2026-05-05

- Created repository for E5 Enclave editorial homepage.
- Added static `index.html` page.
- Added README and agent handoff rules.
- Added GitHub Pages deployment workflow.
