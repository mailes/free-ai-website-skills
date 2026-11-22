# Offcut Studio — estimator landing page (master)

Open index.html in a current browser — no build, no server, no API key needed (works from file:// or any static host).

## What is interactive

- A working project estimator (the core of the page): service type radio, page-count slider (1–30), two per-page add-ons and a rush timeline — the three price cards (agency baseline / freelancer baseline / studio price) update live with the same math the real quotes use.
- "Send this estimate" shows an honest demo note echoing the current estimate and scope — nothing is sent.
- Process, what-you-get, FAQ accordion and contact sections; prefers-reduced-motion renders everything instantly without number tweens.
- Keyboard: radios/checkboxes/slider natively operable, focus-visible outlines.

## Editing (buyer view)

- Pricing math lives in the `calc()` function and `SVC` table (baselines and per-page rates in one place).
- Copy: hero, process, FAQ and contact in the markup. Accent color is `--acc` (one variable).
- Fonts in assets/fonts/ with OFL text. No photos or videos by design — the calculator is the visual.
