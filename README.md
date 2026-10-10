# Bindra Farm

Portfolio of **Naman Bindra**, Senior Software Engineer.

A single-page site set on a living, procedurally drawn farm. In the middle stands a plush nanny goat rendered with WebGPU: soft-body physics (XPBD), shell fur you can comb, and gaits she always recovers from. Click on or near her to open each section of the résumé.

## Run locally

It is one static file, so any static server works:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

WebGPU needs a secure context: `localhost` and HTTPS both work. Use a current Chrome, Edge or Safari.

## Edit the résumé

All content lives in the `RESUME` object near the top of the first `<script>` in `index.html`.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: farm, goat engine, résumé |
| `favicon.svg` | Browser tab icon |
| `404.html` | Friendly not-found page that returns to the farm |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

No images, models or build step. Everything is drawn in code.
