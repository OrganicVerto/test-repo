# Loop & Lark Crochet

A simple 3-page static website for a handmade crochet business.

## Pages

- `index.html` — Home page with an intro and a preview of featured products
- `shop.html` — Full product listing
- `about.html` — About the maker plus a contact section

## Structure

- `styles.css` — shared styling for all pages (colors, layout, components)
- `.claude/launch.json` — local dev server config for previewing the site

## Running locally

This is a static site with no build step. Serve the folder with any static
file server, for example:

```bash
python3 -m http.server 8123
```

Then open http://localhost:8123 in your browser.

## Customizing

The business name, tagline, product details, and contact email are currently
placeholders — update them in `index.html`, `shop.html`, and `about.html`
before publishing.

## Deploying

Since this is plain HTML/CSS, it can be hosted for free with GitHub Pages:
Settings → Pages → Deploy from branch → `main`.
