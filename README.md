# Brush Painting Co. — Website

Website for **Brush Painting Co.**, a painting studio for architectural homes in
Mount Maunganui, Bay of Plenty (NZ). Self-contained static HTML.

The client chose the **Slate & Stone** direction — it's now the live site at
[`index.html`](index.html). The earlier concepts and the (Portuguese) pitch page
are kept in [`archive/`](archive/) for reference.

## Live site
- **Home:** `index.html` — Slate & Stone (dark stone texture + purple)
- Hosted on GitHub Pages → https://vicentevf.github.io/brush-painting/

## Archive (not the live site)
- `archive/index-v1.html` — Concept 01 · Bold & Bright (purple + yellow split hero)
- `archive/index-v3.html` — Concept 03 · Paint Reveal (interactive)
- `archive/showcase.html` — client pitch page (Portuguese), live previews of all concepts

## View locally
Open `index.html` in a browser, or serve the folder (needed for the showcase iframes):

```bash
python -m http.server 8000
# then open http://localhost:8000/
```

## Assets (`images/`)
- `logo.png` — yellow brush. logo (transparent)
- `logo-purple.png` — purple variant (used by the live Slate & Stone site)
- `owner-1.jpg`, `owner-2.jpg` — Arthur & Lucas
- `work-1..9.jpg` — project photos (carousel)
