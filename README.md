# ⚡ EditKit

A free, client-side **PDF & Photo editor** that runs entirely in your browser.
No servers, no uploads, no watermarks — your files never leave your device, and exports are clean originals.

## ✨ Features

### 🖼️ Photo Editor
- Brightness, contrast, saturation, hue, blur, sepia, grayscale
- Rotate, flip (horizontal/vertical)
- Crop by dragging a selection
- Resize (keeps aspect ratio)
- Add text anywhere (click to place, custom size & color)
- Undo history
- Export as PNG / JPEG / WebP at full quality

### 📄 PDF Editor
- Page thumbnails with click-to-select
- Rotate pages
- Delete pages
- Extract page ranges (e.g. `1-3,5`)
- Merge multiple PDFs
- Stamp text on pages (position + opacity)
- Download clean, standard PDFs

## 🚀 Run locally

No build step. Just open the file:

```bash
git clone https://github.com/Haziqbaig/editkit.git
cd editkit
# open index.html in your browser, or serve it:
python3 -m http.server 8000
# → http://localhost:8000
```

## 🌐 GitHub Pages

This repo is deployable straight to GitHub Pages (it's a single static `index.html`).

## 🔒 Privacy

All processing happens locally via HTML5 Canvas, [pdf-lib](https://pdf-lib.js.org/) and [PDF.js](https://mozilla.github.io/pdf.js/). Nothing is uploaded anywhere.

## License

MIT
