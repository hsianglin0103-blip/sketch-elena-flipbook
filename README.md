# Sketch Elena — Flipbook

**View it:** https://hsianglin0103-blip.github.io/sketch-elena-flipbook/

A page-turning web viewer for the Sketch Elena book: 30 drawings on 12 × 12 in square pages, each with a page number at the bottom.

Open `index.html` in a browser, or publish the folder with GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

- `pages/` holds the full-size page images, `thumbs/` the previews.
- Page order is set by the `RAW` list near the top of the script in `index.html`.
- Page turning uses [StPageFlip](https://github.com/Nodlik/StPageFlip) 2.0.7 (MIT), bundled in `vendor/`.

Controls: click a page or drag a corner to turn, ← / → keys, Home / End, G for all pages, Z for zoom, F for full screen. Link to a page with `#p12`.
