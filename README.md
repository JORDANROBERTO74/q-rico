# Q'Rico — Cocina honesta

Landing page for a (fictional) restaurant. A frontend showcase built with **vanilla HTML, CSS and JavaScript** — no frameworks, no build step, no UI libraries.

## Highlights

- **Editorial design system**: warm palette (espresso / cream / terracotta), serif display (Playfair Display) + sans body (Inter), fluid type scale with `clamp()`.
- **Real restaurant structure**: hero, specialties, **menu with categories and prices**, about/chef, gallery, reviews, reservation form.
- **Responsive**: from 320px to 1440px, mobile-first, no overflow.
- **Accessible (WCAG 2.1 AA)**: skip link, semantic landmarks, visible focus, labeled form fields, `prefers-reduced-motion`.
- **Performance**: WebP images (~2.72 MB → ~0.7 MB), no carousel library, no icon fonts (inline SVG).
- **SEO**: meta description, Open Graph/Twitter, JSON-LD `Restaurant`, favicon.

## Stack

- HTML5
- CSS3 (custom properties, Grid, `clamp()`)
- Vanilla JS (accessible nav, scroll reveal, form validation — no dependencies)

## Structure

```
index.html
styles.css
main.js
favicon.svg
.nojekyll
img/
  *.webp   # optimized images
  *.jpg / *.png  # originals (fallback / source)
```

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8080
```

Then visit <http://localhost:8080>.

## Live preview

<https://jordanroberto74.github.io/q-rico/>

## Notes

- **Demo / fictional content**: menu, prices, address, phone and reviews are illustrative.
- The reservation form is **front-end only**: it validates fields and shows a success state; no backend.

## Contact

[jordanroberto74@gmail.com](mailto:jordanroberto74@gmail.com)
