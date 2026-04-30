# Trade Screen Prototype

Position visibility & accessibility issues — Mobile trading screen prototype.

## Live Demo

Once GitHub Pages is enabled: `https://<USERNAME>.github.io/<REPO>/`

## Features

- **Positions tab (4 cards)** — Isolated/Cross modes, with/without TP/SL
- **Orders tab (6 cards)** — TPSL Limit, Limit, Trigger order types
- **Show all symbols** toggle — filter by current symbol (BTC) when off
- **Size unit toggle** — click `Size (USDT)` label area to switch to symbol unit (BTC/ETH/XRP/VELODROME)
- **Action menu (⋮)** — Add Position / Adjust Margin (Isolated only) / Adjust Leverage / Flip
- **Responsive** — adapts to device width (320px ~ 430px+)

## Local development

```bash
# Just open index.html in a browser, or serve with any static server:
python3 -m http.server 4008
# Then open http://localhost:4008
```

## Stack

- Single HTML file (no build step)
- Inline CSS / Vanilla JS
- Pretendard font via CDN
