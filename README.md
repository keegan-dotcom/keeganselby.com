# keeganselby.com

Personal site for Keegan Selby — Co-Founder & GP at [Fourth Revolution Capital](https://www.fourthrevolution.capital), venture builder at Selby Studio.

**Live:** [keeganselby.com](https://www.keeganselby.com)

## Stack

Single-file static site (`index.html`) — no build step, no dependencies beyond CDN scripts. Deployed on Vercel.

- Custom canvas "cosmos" background: parallax starfield, orbital mechanics, comets, UFO squadron with cursor-hunting AI
- Space Grotesk + IBM Plex Mono, tactical dark theme (#0a0a0a / #ff5c1f)
- Interactive modes: X-Games, Hyperdrive, Encore, MAX CHAOS, Boring Mode
- Konami code easter egg (↑↑↓↓←→←→BA), Tony Hawk-style score meter, idle cursor-abduction gag
- Optional synthesized WebAudio sound (click-to-arm, no autoplay)

## Structure

```
index.html              — the entire site
og.png                  — social share image
apple-touch-icon.png    — iOS icon
papers/                 — hosted PDFs (Cosmic Karma, Where is Everybody?)
versions/               — design alternates (v1 tactical, v2 editorial)
```

## Deploying

The Vercel project (`keeganselby`, Selby Studio team) serves production at keeganselby.com. Deploy by pushing to this repo (if Git integration is connected) or via `vercel deploy --prod` from the repo root.
