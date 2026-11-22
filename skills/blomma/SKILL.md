---
name: blomma
description: Adapt the Blomma fragrance landing page for a scent, beauty or small-batch goods brand, with scent panels, mood filtering, size selection and a local demo cart.
---

# Blomma

Read README.md. Open the bundled index.html and REUSE-HERBARIUM.html — a completed second-brand adaptation of the same master. Collect a brand name, three hero title lines, two scent-panel labels (soft/wild words), two panel product names with three notes each, and a product list with moods and prices, then update `PRODUCTS`, the panel markup and the copy. The shop grid, mood filters, size pricing and cart all read from `PRODUCTS`.

Never invent a real fragrance house or claim real ingredients; keep the fictional-demo notes. Checkout intentionally shows a demo notice — wire it to a real store only when one exists.

Preserve the entrance system (1600ms cubic-bezier(0.22,1,0.36,1), hero stagger 100..1300ms, panel IO 0.15 with the 0/300/600/900/1150 stagger), the pill filters, per-size pricing and the reduced-motion behavior (all five films held on first frame). Keep the white field with blue/lime panels.

Verify at 1440px and 390px: title breakpoints exclusive, panels split 1:1 on desktop with the correct video side, filters/sizes/cart math exact, no console errors, no horizontal overflow.
