# Coco in Clutch

Luxury evening clutch showcase site. Static, no build step on the host.

- Source of truth: `coco-main/coco-in-clutch/tools/` (`build.mjs` + `template.html` + `products.mjs`, from Gemini analysis of the shelf photos)
- Rebuild: `node tools/build.mjs`, then copy `site/` here and push. GitHub Pages serves `main` root.
- Design (Oct 2026 redesign): maison-style layout, Bodoni Moda wordmark "COCO in CLUTCH" + Jost, palette cream #f6f1e9 / black #0e0d0c / gold #b39462. Every product shows "Price on Request" with a WhatsApp enquiry (ref CIC-001..022), a saved "Selection" that enquires in one message, and a cookie consent banner + preference centre (choice stored in localStorage `cic-consent-v1`).
- Preview with all sections visible (no scroll reveal): open `index.html?static`.
- Prices: the site shows "Price on Request" everywhere; `PRICES` in `tools/build.mjs` is kept for later.
- Product images are Gemini 2.5 Flash Image studio renders of the real stock, illustrative.
