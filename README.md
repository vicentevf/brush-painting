# Brush Painting Co. — Website Concepts

Three home-page concept directions for **Brush Painting Co.**, a painting studio for
architectural homes in Mount Maunganui, Bay of Plenty (NZ). Each is a self-contained
static HTML page that shares the same content below the hero.

## Concepts

| File | Concept | Look |
|------|---------|------|
| [`index.html`](index.html) | **01 · Bold & Bright** | Split hero, purple + yellow |
| [`index-v2.html`](index-v2.html) | **02 · Slate & Stone** | Dark stone texture, purple |
| [`index-v3.html`](index-v3.html) | **03 · Paint Reveal** | Interactive — paint colour onto the hero |
| [`presentation.html`](presentation.html) | **Showcase** | Live previews of all three, for the client |

## View it

Open any HTML file in a browser. To make the `presentation.html` live previews work,
serve the folder over HTTP (browsers block local `file://` iframes):

```bash
python -m http.server 8000
# then open http://localhost:8000/presentation.html
```

On **GitHub Pages** everything works over https with no extra steps.

## Assets
- `images/logo.png` — yellow brush. logo (transparent)
- `images/logo-purple.png` — purple variant (used by Concept 02)
- `images/owner-1.jpg`, `owner-2.jpg` — Arthur & Lucas
- `images/work-1..9.jpg` — project photos (carousel)
