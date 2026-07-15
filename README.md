# Ronak Sharma — Portfolio

A single-page personal portfolio with a hand-drawn, sketchbook-style visual theme — doodle borders, sticker-style badges, and playful micro-interactions layered over a clean, information-dense layout.

🌐 **Live:** [ronaksharma.vercel.app](https://ronaksharma.vercel.app)

## Overview

Built as a static, single-file site (HTML/CSS/vanilla JS) showcasing background, skills, projects, education, and contact info. No framework, no build step — just structured CSS with design tokens and a handful of small interactive scripts.

## Features

- **Doodle / neubrutalism visual theme** — hard borders, offset drop shadows, hand-drawn accents (`Kalam` display font + `Inter` body + `JetBrains Mono` for code-styled text)
- **Animated hero section** — staggered entrance animations, rotating role text, confetti burst on CTA click
- **Scroll-reveal animations** via `IntersectionObserver`
- **Active nav-link highlighting** synced to scroll position
- **Mouse-tilt project cards** with a lightweight parallax effect
- **Responsive** — collapses to a mobile hamburger nav under 700px, with animations disabled under `prefers-reduced-motion`
- **Sections:** Hero, About, Skills, Projects, Education, Contact

## Tech Stack

- HTML5 / CSS3 (custom properties for theming, no preprocessor)
- Vanilla JavaScript (no dependencies beyond CDN fonts + Font Awesome icons)
- Deployed on Vercel

## Project Structure

```
portfolio/
└── index.html   # Everything — markup, styles, and scripts in one file
```

## Running Locally

No build step required.

```bash
git clone https://github.com/Ronakkkkkkk/portfolio-v2.git
cd portfolio-v2
```

Then just open `index.html` in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Customizing

- **Colors / theme:** edit the CSS custom properties in `:root` at the top of the `<style>` block
- **Content:** hero text, skills, projects, and education are plain HTML — edit directly in the relevant `<section>`
- **Rotating role text:** edit the `roles` array near the bottom of the `<script>` block

## Author

Ronak Sharma
GitHub: [github.com/Ronakkkkkkk](https://github.com/Ronakkkkkkk)