# Movie Mazza Landing Page

A movie-subscription landing page prototype using HTML, CSS, and vanilla JavaScript. The interface contains a hero section, feature tabs, and a sample plan-comparison table.

## Repository structure

| Path | Purpose |
| --- | --- |
| `index.html` | Landing-page markup and sample plan content |
| `styles.css` | Page styling |
| `action.js` | Tab-selection event handlers |
| `img/` | Local visual assets |

## View locally

```bash
git clone https://github.com/yash1286/MovieMazza_website.git
cd MovieMazza_website
python -m http.server 8000 --bind 127.0.0.1
```

Open [localhost:8000](http://localhost:8000). Python is only needed for this optional local server; the page has no build step.

## Current behavior and limitations

- The page is a static interface prototype. Sign-in, subscriptions, and streaming are not implemented.
- Prices, offers, dates, and contact details are sample interface content.
- `action.js` currently loads before the tab elements exist. Move the script to the end of the body, or load it with `defer` from the head, before expecting the tab handlers to work.
- Some images use external URLs, and Font Awesome icon classes appear without a corresponding icon stylesheet.
- Links use placeholder destinations.
- Cross-browser behavior and accessibility have not been verified.

## Skills represented

HTML page structure, CSS layout, DOM selection, event listeners, and class-based state changes. This repository is a frontend exercise and does not include a data processing backend.
