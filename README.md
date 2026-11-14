# Trends over Decades

A website about how fashion changed from the 1960s to the 2000s, one decade per page: Jackie Kennedy's tailored suits and mod miniskirts, '70s afros and bell-bottoms, '80s neon and power shoulders, '90s grunge and hip-hop, and Y2K low-rise and velour.

**View it:** https://nmeko.github.io/trends-over-decades/ (free, in the browser, nothing to install)

**Built with:** HTML and CSS, no frameworks and no build step. It works on phones, tablets and desktops, and runs as-is on GitHub Pages.

## Pages

| Page | What's on it |
|---|---|
| `index.html` | Introduction and a card for each decade |
| `1960s.html` | Early, mid and late '60s styles, top influencers, a price catalog and a video |
| `1970s.html` | Key styles, a photo gallery, a price table, a video and a source for more |
| `1980s.html` | Outfit catalog, a price table, a video and a source for more |
| `1990s.html` | Trends, icons, accessories, a price table, a video and a source for more |
| `2000s.html` | Signature Y2K looks, a price table, a video and a source for more |

## Run it

Open `index.html` in a browser. To publish it, turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).

## Structure

```text
index.html, 1960s.html … 2000s.html   pages
assets/css/style.css                   one shared stylesheet; each decade sets its accent color
assets/img/                            logo and photos, organized by decade
```

## Team

Made by Fashion Team 5. Each team member researched and built one decade's page.

## Prices

Every decade page has a "then vs. now" table. Original prices link to their sources, and today's prices are adjusted into 2024 dollars with the U.S. Consumer Price Index (BLS CPI-U): price × (2024 CPI ÷ CPI in that year).
