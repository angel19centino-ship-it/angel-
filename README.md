# ANGEL® — Grace, engineered.

A single-file, liquid-chrome landing page with one job: **book a call.**

**Live at → https://angel19centino-ship-it.github.io/angel-/**

Every push to the default branch redeploys automatically: the
`Deploy to GitHub Pages` workflow republishes `index.html` to the
`gh-pages` branch, which GitHub Pages serves.

- **Stack** — one `index.html`. Three.js (raymarched chrome + halo, CDN) and GSAP ScrollTrigger (CDN). No build step: open the file or host it anywhere (GitHub Pages, Netlify, Vercel).
- **Motion** — loader counter, masked headline reveal, scroll-scrubbed manifesto, velocity-reactive marquee, count-up stats, right-edge scroll progress rail, and a chrome sculpture that melts apart as you scroll and reassembles behind the final CTA.
- **Respectful** — honors `prefers-reduced-motion` (static chrome frame, no tweens, final values shown), works with JavaScript or CDNs unavailable, and is fully responsive.

## SERAPH® — snake, ascended

The repo also ships a game: `snake/index.html`, a single-file,
zero-dependency take on Snake in the same liquid-chrome style.
Steer a ribbon of chrome, gather motes of light, and grab the golden
halo that appears after every fifth one (worth five points, on a
seven-second timer). Arrow keys / WASD or swipe; Space pauses; best
score is remembered locally.

**Play at → https://angel19centino-ship-it.github.io/angel-/snake/**
(deploys with the site on the next push to the default branch)

## SWEEP® — grace, restored

A second game, built from four real photos of the house: `sweep/` is a
point-and-click cleanup quest. Mom is home in 3:00 — tap every piece of
clutter in the dining room, living room, game room, and backyard before
the clock runs out. The dartboard, punching bag, and basketball hoop in
the photos are playable mini-games worth bonus points. Works with mouse
or touch; best score is remembered locally.

**Play at → https://angel19centino-ship-it.github.io/angel-/sweep/**

## VIGIL® — 3:00 AM

The horror sequel to SWEEP®: `vigil/` is a first-person 3D game built
on a zero-dependency raycasting engine. Walk the house at 3 AM by
flashlight — the walls are textured with crops from the real photos
(the wood paneling, the stone fireplace, the hedge, the stucco). Find
the four framed memories to open the back gate, and don't let the
thing that lives there catch you. WASD + mouse (or touch) to move,
E to take a memory, SHIFT to run. Headphones recommended.

**Play at → https://angel19centino-ship-it.github.io/angel-/vigil/**

## HEARTH® — walk your home

`hearth/` is a bright, peaceful first-person 3D walkthrough of the house
— the calm counterpart to VIGIL®. Built on the same zero-dependency
raycasting engine, but each of the four rooms has its **real photograph
mounted on the far wall**, so you literally walk from inside the picture:
the dining room, living room, game room, and backyard, all connected by
doorways, with a live minimap. No monster, no timer — just explore.
WASD + drag-to-look (or touch), SHIFT to jog.

**Walk in at → https://angel19centino-ship-it.github.io/angel-/hearth/**

## Customize

Everything to change is marked with a `CUSTOMIZE ME` comment at the top of `index.html`:

1. **Booking link** — set `BOOK_URL` in the first `<script>` block (e.g. your Calendly/Cal.com URL), or replace the `mailto:` hrefs.
2. **Stats** — edit the `data-count` values in `<section id="numbers">`.
3. **Selected work** — the four projects are placeholders; swap in your own.
4. **Availability line** — search for `Q3 2026`.
