# TDev Spot — Cinematic Ad

A self-playing, 18-second cinematic brand spot for **TDev**, hand-built with vanilla **HTML, CSS and Canvas** — no frameworks, no build step, one file.

**▶ Live demo:** https://talhaasajjad.github.io/tdev-cinematic-ad/

![TDev](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20Canvas-5b8cff) ![No build](https://img.shields.io/badge/build-none-28e0b0)

## What it does

The ad plays automatically as a timed five-scene sequence over a live particle network, graded with a cinematic letterbox, vignette, film grain and anamorphic light sweeps:

1. **Cold open** — tagline reveal with a blur-focus rise
2. **Code editor** — a `ship.ts` file that writes itself line by line, syntax-highlighted
3. **Product UI** — a TDev console that assembles itself, with an animated line chart
4. **Kinetic type** — "Design. Develop. Deploy." punching in word by word
5. **Logo reveal** — the TDev wordmark, accent rule, and contact

Press **Replay** to watch it again.

## Tech

- Pure HTML/CSS, CSS keyframe choreography, and a `<canvas>` particle field drawn with `requestAnimationFrame`
- A small vanilla-JS timeline driving scene transitions
- Fully responsive (16:9 that scales to phone width), respects `prefers-reduced-motion`
- Zero dependencies — just open `index.html`

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## About

Built by **Talha Sajjad (TDev)** — software developer.

- GitHub: [@TalhaaSajjad](https://github.com/TalhaaSajjad)
- Email: talhabinsajjad1234@gmail.com
- Portfolio: https://talhaasajjad.github.io/portfolio/

> Open to work — if you'd like something like this for your product, get in touch.
