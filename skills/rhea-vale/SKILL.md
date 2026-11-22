---
name: rhea-vale
description: Adapt the Rhea Vale 3D creator portfolio for a 3D artist, motion designer or industrial visualization studio, featuring a magnetic hero centerpiece, dual counter-scrolling showreel, scroll-lit manifesto, light services contrast band, sticky scaling project cards and hash-routed case detail overlays.
---

# Rhea Vale

Read `README.md`. Open the bundled `index.html` and `REUSE-KESTREL.html` — a completed second-brand adaptation of the same master for an industrial visualization director. Collect a creator/studio name, hero greeting, tagline, about statement, services list and 3+ portfolio projects (each with 3 renders, metadata, process steps, deliverables and outcome), then update the markup and the `SERVICES` / `PROJECTS` data arrays in `index.html`.

Replace `assets/hero-object.png` (transparent PNG centerpiece), `assets/deco-*.png` (four corner objects), `assets/case-<slug>-{a,b,c}.webp` and `assets/reel-01..16.webp` with same-named rights-cleared renders. Keep `PROJECTS` slugs aligned with image filenames so stacked cards, hash routes (`#work/<slug>`), and Prev/Next case navigation stay in sync. Keep the fictional-demo notice in the footer until replaced with real studio credentials.

Preserve the motion grammar: staggered hero entry (0/150/350/500/600ms), magnetic hero follow (`offset / 3` with smooth snap-back), dual counter-scrolling reel (`±0.3×`), word-wrapped character-by-character About illumination, sticky stacked project cards with progressive scale-down (`1 - (N-1-i)*0.03`), accessible dialog focus trap + scroll-position restoration, and full `prefers-reduced-motion` gating.

Verify at 1440px and 390px: About paragraph wraps cleanly without overflow, every project card opens/closes via click, Enter, Esc and browser Back, reduced-motion shows all content immediately, zero broken assets and zero console errors.
