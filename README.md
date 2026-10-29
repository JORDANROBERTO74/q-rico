# Q'Rico — Cocina Honesta

A restaurant landing page built around the menu: categories, prices, gallery, reviews and a reservation form. Hand-written HTML, CSS and JavaScript, with no framework or build step.

![Q'Rico home page with a warm dark hero, the headline "Comida honesta, sabor que se recuerda" and a row of dish photographs](docs/screenshot.webp)

## What it is

A one-page site for a fictional restaurant in Santa Cruz, Bolivia: hero, specialties, a full menu with categories and prices, the chef's story, gallery, reviews and a reservation form.

It is a front-end showcase, not a booking product. The form validates in the browser and shows a success state; there is no backend, database or payment flow.

## Why this over a restaurant template

- **Editorial design system.** Espresso, cream and terracotta; Playfair Display for headings, Inter for text and a fluid `clamp()` type scale.
- **The menu is the product.** Categories, dish names and prices are structured content, not a gallery of images — the page works the way a real menu does.
- **Accessible (WCAG 2.1 AA).** Skip link, semantic landmarks, visible focus, labeled fields and `prefers-reduced-motion`.
- **Performance.** WebP images (~2.72 MB reduced to ~0.7 MB), inline SVG icons and no carousel or icon library.
- **SEO.** Meta description, Open Graph/Twitter cards and `Restaurant` JSON-LD.

## Quick start

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8080
```

Visit <http://localhost:8080>.

## Project structure

```text
index.html              # The whole page
styles.css              # Design tokens, layout and components
main.js                 # Accessible nav, scroll reveal, form validation
img/                    # Optimized WebP images
docs/screenshot.webp    # README screenshot
```

## Status and scope

Live at <https://jordanroberto74.github.io/q-rico/>. Menu, prices, address, phone and reviews are illustrative. The reservation form is front-end only: it validates and shows a success state, but sends nothing.

## License

MIT. See [LICENSE](LICENSE).
