---
name: canto
description: Build a light-mode online learning, cohort academy, or EdTech SaaS website featuring an expanding 3-card vertical-label accordion hero, peach-to-sage search bar, live course filter, slide-over syllabus drawer, study plan bookmarking, and mastery pace/team tuition calculator.
---

# CANTO — Light-Mode Online Learning & Cohort Platform Skill

Use this skill when building a bright, editorial, conversion-focused website for an online academy, cohort-based course platform, design school, or B2B training SaaS.

## What You Receive
- `index.html` — Complete standalone landing page (pure HTML + CSS + vanilla JS, zero external CDNs).
- `assets/fonts/` — Local SIL OFL `Manrope` (`manrope-variable.ttf`) and `Inter` (`inter-400..700.ttf`) font files.
- `assets/media/` — 3 cohesive original editorial studio portraits (`track-design.jpg`, `track-engineering.jpg`, `track-strategy.jpg`).
- `README.md` & `SOURCES.md` — Setup guide and per-file SHA-256 provenance ledger.

## Architecture & Adaptation Playbook
1. **Palette & Editorial Surface Tokens (`:root`)**:
   - Ground `--bg-soft: #F4F4F2`, crisp cards `--bg-surface: #FFFFFF`, primary navy `--ink-main: #1A1E2D`.
   - Swap `--accent-peach` (`#FDB181`) and `--accent-sage` (`#8BBF77`) to shift the dual-tone search button hover fill and track badges to your target brand palette.
2. **3-Card Expanding Accordion Hero**:
   - Replace the 3 `900×1206` vertical portraits in `assets/media/` and edit the `.track-card` labels (`data-track`, `.vertical-pill`, `.track-card-title`, `.num`).
   - Keep `flex: 2.55` (expanded) vs `flex: 0.85` (collapsed) with `cubic-bezier(0.23, 1, 0.32, 1)` for smooth desktop transitions and horizontal snap-scroll on mobile.
3. **Live Catalog & Syllabus Drawer**:
   - Edit the `COURSES` array in `<script>` to update track names, instructors, seat counts, and weekly syllabus modules.
   - Clicking any card's `Inspect Syllabus` opens the accessible right-hand slide-over drawer (`Escape` + backdrop dismissal).
4. **Mastery Pace & Tuition Planner**:
   - Adjust base tuition rates (`$39/mo` individual, `$29–$34/seat` team) and completion formulas inside `updatePlanner()`.
5. **Honest Form Handling**:
   - Wire `#trialForm` to your actual backend or waitlist API before deploying; never fake a completed subscription in local preview mode.

## Quality Checklist Before Shipping
- Serve over HTTP (`python3 -m http.server`) and verify `0` console errors and `0` failed requests.
- Confirm `overflowX === false` at `1440×900` and `390×844`.
- Confirm all 3 editorial portraits and local `@font-face` fonts load offline.
