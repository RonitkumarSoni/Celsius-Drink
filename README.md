# Celsius Energy — Scroll Experience

A cinematic, scroll-driven landing page for the **Celsius Energy** drink brand, built as a front-end showcase of advanced GSAP animation, pinned sections, and clip-path reveals. Every section is choreographed to the scrollbar: titles wipe in, cans slide through a horizontal slider, videos pin and play, and a fluid "drip" mask transitions between sections.

<p align="center">
  <img src="public/celsius-logo.svg" alt="Celsius Energy" width="120" />
</p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white" />
  <img alt="GSAP" src="https://img.shields.io/badge/GSAP-ScrollTrigger-88CE02?logo=greensock&logoColor=white" />
</p>

---

## Demo

**Live:** https://RonitkumarSoni.github.io/Celsius-Drink/

---

## Highlights

- **Animated preloader** — a full-screen loader reveals the Celsius logo via a `clip-path` wipe synced to a 0→100% counter and progress bar, then fades out and gates the site render until loading completes.
- **Scroll-choreographed storytelling** — each section is timed to scroll progress with GSAP `ScrollTrigger` (`scrub`, pinning, and timeline reveals).
- **Clip-path title reveals** — headlines wipe into view with animated `clip-path` polygons for a premium editorial feel.
- **Horizontal flavor slider** — product cans scroll sideways while the page scrolls vertically, with splash artwork using `mix-blend-mode`.
- **Pinned video sections** — hero and testimonial videos pin to the viewport and play/pause on interaction.
- **Drip mask transitions** — PNG `mask-image` "drip" dividers melt one section into the next.
- **Responsive by design** — `react-responsive` plus Tailwind breakpoints adapt layouts and animation timing from mobile to 2XL.
- **Cohesive design system** — a single brand palette and neutral scale exposed as Tailwind v4 `@theme` tokens, with WCAG-AA contrast on interactive elements.

---

## Tech Stack

| Layer        | Choice                                  |
| ------------ | --------------------------------------- |
| Framework    | React 19                                |
| Build tool   | Vite 6                                   |
| Styling      | Tailwind CSS 4 (`@tailwindcss/vite`)     |
| Animation    | GSAP 3 + `@gsap/react` (`useGSAP`)       |
| Scroll engine| GSAP `ScrollTrigger`, `SplitText`        |
| Responsive   | `react-responsive`                       |

---

## Getting Started

**Prerequisites:** Node.js 18+ and npm.

```bash
# install dependencies
npm install

# start the dev server (http://localhost:5173)
npm run dev

# build for production into /dist
npm run build
```

---

## Author

**Ronit Soni**

---

## Disclaimer

This is an **unofficial, non-commercial project** created for educational and portfolio purposes. *Celsius* and all related names, logos, and product imagery are trademarks of their respective owners and are used here purely to demonstrate front-end and animation craft. Not affiliated with or endorsed by Celsius Holdings, Inc.
