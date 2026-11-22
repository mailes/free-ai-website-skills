---
name: offcut
description: Adapt the Offcut Studio dark estimator landing page for a freelance studio, productized agency or consulting service, with a live scope-and-page estimator, agency/freelancer baseline comparison cards, itemized breakdown, reset action and honest demo inquiry echo.
---

# Offcut Studio

Read `README.md`. Open the bundled `index.html` and `REUSE-KILN.html` — a completed second-brand adaptation of the same master for a brand & packaging studio. Collect a brand name, accent color (`--acc`), hero copy, service tiers (`SVC` base & per-page rates), add-on rates, timeline multipliers, included deliverables, process steps and FAQ items, then update the markup and the `SVC` / `calc()` logic in `index.html`.

Keep the estimate breakdown line (`#breakdown`), savings badge (`#savePill`), three comparison cards (`#agency`, `#freelancer`, `#yours`), reset button (`#resetBtn`) and honest demo inquiry note (`#sendNote`) driven from the same `calc()` output so numbers never drift. Never display fake "Quote sent" confirmations when no backend is connected.

Preserve the dark-canvas high-contrast surface (`#0D0D0D` / `#161616`), custom radio/checkbox/range-slider `--fill` states, 400ms number tween with instant `prefers-reduced-motion` fallback, and responsive layout from 390px to 1440px.

Verify at 1440px and 390px: hand-check estimator math across two service modes, slider extremes (1 and 30 pages), add-ons, rush timeline and Reset; verify zero console errors and zero horizontal overflow.
