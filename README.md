# Painting AR
Scan the QR beside the painting → `https://yashwa39.github.io/ar/?p=krishna` → tap **Start AR** → point at the canvas.
A lit, glowing 3D moon appears inside the painted moon (behind the figure) and tracks the canvas in real time.

- `index.html` – the whole app (three.js + MindAR image tracking)
- `assets/krishna.jpg` – tracking target (cropped canvas), `krishna.mind` – precompiled target, `krishna-mask.png` – moon mask
- `vendor/` – self-hosted three.js 0.160 + MindAR 1.2.5 (no CDN needed)
- Add a painting: new entry in `PAINTINGS` in `index.html`, new assets, QR → `?p=<id>`
