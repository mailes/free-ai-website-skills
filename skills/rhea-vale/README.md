# Rhea Vale — 3D Creator Portfolio (master)

Open `index.html` in Chrome or another current browser — no build, no server, no API key needed (works from file:// or any static host).

## What is interactive

- Browse the render reel (scroll-driven, two counter-moving rows).
- Choose one of three projects in the stacked Work cards → the full case study opens (brief, process, gallery, deliverables, outcome) → return via the Back button, `Esc`, or the browser back button. Scroll position and keyboard focus are restored.
- Case studies are addressable via hash routes (`#work/porcelain-goods`) and can be reached with the browser's back/forward buttons.
- About paragraph reveals character-by-character on scroll; hero portrait follows the cursor magnetically (desktop pointers only).
- `prefers-reduced-motion` renders the whole page static and fully readable; keyboard operation covers nav, cards, case dialog (`Esc` closes) and focus-visible outlines.

## Editing (buyer view)

- Brand, tagline, services, projects and case copy live in the `SERVICES` and `PROJECTS` arrays plus the hero/about/footer markup in `index.html` — edit in one place, cards and case views update together.
- Swap artwork by replacing same-named files in `assets/` (`hero-object.png`, `deco-*.png`, `case-<slug>-*.webp`, `reel-*.webp`). Card and case views share the same three images per project.
- Fonts sit in `assets/fonts/` with `@font-face` declared at the top of the stylesheet; keep the four weight files or update both the `@font-face` block and `OFL.txt` if you substitute a typeface.
- Keep the animation offsets/timing (see project MOTION.md) unless a client asks for changes.
