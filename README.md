# Coco in Clutch

Luxury evening clutch showcase site. Static, no build step on the host.

- Source of truth: `coco-main/coco-in-clutch/tools/` (`build.mjs` + `template.html` + `products.mjs`, from Gemini analysis of the shelf photos)
- Rebuild: `node tools/build.mjs`, then copy `site/` here and push. GitHub Pages serves `main` root.
- Prices: set per product in `PRICES` in `tools/build.mjs` (currently "Price on request").
- Product images are Gemini 2.5 Flash Image studio renders of the real stock, illustrative.
