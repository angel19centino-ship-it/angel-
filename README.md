# ANGEL® — Grace, engineered.

A single-file, liquid-chrome landing page with one job: **book a call.**

- **Stack** — one `index.html`. Three.js (raymarched chrome + halo, CDN) and GSAP ScrollTrigger (CDN). No build step: open the file or host it anywhere (GitHub Pages, Netlify, Vercel).
- **Motion** — loader counter, masked headline reveal, scroll-scrubbed manifesto, velocity-reactive marquee, count-up stats, right-edge scroll progress rail, and a chrome sculpture that melts apart as you scroll and reassembles behind the final CTA.
- **Respectful** — honors `prefers-reduced-motion` (static chrome frame, no tweens, final values shown), works with JavaScript or CDNs unavailable, and is fully responsive.

## Customize

Everything to change is marked with a `CUSTOMIZE ME` comment at the top of `index.html`:

1. **Booking link** — set `BOOK_URL` in the first `<script>` block (e.g. your Calendly/Cal.com URL), or replace the `mailto:` hrefs.
2. **Stats** — edit the `data-count` values in `<section id="numbers">`.
3. **Selected work** — the four projects are placeholders; swap in your own.
4. **Availability line** — search for `Q3 2026`.
