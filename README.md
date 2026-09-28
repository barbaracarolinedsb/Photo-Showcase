# Photo Showcase

A single-page HTML project that showcases some of the best places to visit in the world. The goal is to practice handling images, captions, and embedded media with semantic, accessible markup. The page is intentionally **unstyled**; CSS is left for a later project.

## What this project covers

- **Semantic page structure** with `<header>`, `<main>`, and `<footer>`
- **Images** with descriptive `alt` text and `width`/`height` attributes to reserve layout space and avoid layout shifts
- **Captions** using `<figure>` and `<figcaption>`
- **Lazy loading** with `loading="lazy"`
- **Embedded video** with `<video>`, including `controls`, `poster`, and fallback content
- **Head metadata**: `<title>`, `<meta charset>`, `<meta viewport>`, plus `description` and `keywords`

## Page content

| Section | Description |
| --- | --- |
| Header | Page title, short welcome text, and navigation links |
| About this page | Short introduction to the showcase |
| Gallery | Six images, each inside a `<figure>` with a `<figcaption>` |
| Video | An embedded `.mp4` with a poster image and fallback link |
| Footer | Copyright notice |

### Gallery images

| File | Place |
| --- | --- |
| `italy.jpg` | Cinque Terre coastline, Italy |
| `Northernlights.jpeg` | Northern Lights (aurora borealis) |
| `castle.jpg` | Neuschwanstein Castle, Bavaria, Germany |
| `antarctica.png` | Penguins and an ice wall, Antarctica |
| `tajmahal.png` | Taj Mahal, Agra, India |
| `lagodibraies.png` | Lago di Braies, Dolomites, Italy |

## Project structure

```
Photo-Showcase/
├── index.html
├── italy.jpg
├── northernlights.jpeg
├── castle.jpg
├── antarctica.png
├── tajmahal.png
├── lagodibraies.png
├── poster.jpg
└── README.md
```

## Accessibility notes

- `<figcaption>` adds **extra context** for everyone, such as the location or a short fact.
- The `<video>` includes fallback text and a download link for browsers that do not support it.
- Headings follow a logical hierarchy (`h1` → `h2` → `h3`).

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/barbaracarolinedsb/Photo-Showcase.git
   ```
2. Open the folder and double-click `index.html`, or open it in your browser.

No build step or dependencies are required.

## Media credits

- Video: [MDN interactive examples](https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4) (CC0)
- Photos: Photo by <a href="https://unsplash.com/@rocinante_11?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Mick Haupt</a> on <a href="https://unsplash.com/photos/brown-wooden-boat-on-lake-during-daytime-pg8k1mZPMRg?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
Photo by <a href="https://unsplash.com/@gabrielrana?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Gabriel Tovar</a> on <a href="https://unsplash.com/photos/a-large-castle-with-towers-surrounded-by-trees-UkbotMeO8Jw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
Photo by <a href="https://unsplash.com/@vingtcent?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Vincent Guth</a> on <a href="https://unsplash.com/photos/silhouette-of-trees-near-aurora-borealis-at-night-62V7ntlKgL8?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

## License

All rights reserved. Replace this section with a license of your choice if you want to share the project openly.
