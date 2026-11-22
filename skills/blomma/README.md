# Blomma — small-batch fragrance landing page (master)

Open index.html in a current browser — no build, no server, no API key needed.

## What is interactive

- Full-screen meadow hero with the spec's staggered entrance (title lines, scroll cue, slide index, floating product card).
- Two scent panels (blue "Blomma soft" / lime "Blomma wild") with IntersectionObserver staggers; each SHOP NOW jumps to the shop pre-filtered by mood.
- Shop: mood filter (All/Sweet/Playful/Bold), 50/100 ml size selection (50 ml is $45 less), add-to-cart from the grid or the hero card, and a local cart bar with line items and total. Checkout shows an honest demo note — nothing is charged.
- prefers-reduced-motion: everything visible instantly, all five films held on their first frame.

## Editing (buyer view)

- Products live in the `PRODUCTS` array (names, sizes, moods, prices); mood filter pills in the shop markup.
- Films: assets/hero-film.mp4, scent-film.mp4, wild-film.mp4 (replace with same-named silent seamless loops).
- Product photos: assets/product-1..3.webp — real CC/PD photographs, see SOURCES.md credits.
