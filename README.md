# PBC Explainer

A plain-language, interactive companion to the research paper
**"Pixel Block Chain: Spatial Tamper Localization and Crop-Resilient Edit Ledger
for Images in the Wild"** (François Légaré, Sion Israel Sion, Alain April — IEEE ICIP 2026).

Live site: **https://pbc.mobidroid.com**

A single self-contained `index.html` (no build step, no dependencies) with:

- A layered explanation — plain English up top, "Go deeper" expanders for the mechanism.
- Four interactive `<canvas>` demos: LSB reveal, click-to-tamper localization,
  single-chain-vs-grid cascade, and a crop-survival simulator.
- Language switcher: **English · Français · Español** (extensible — add a block to `I18N`).
- The paper's real figures and the verified benchmark numbers.

The reference implementation and paper live at
<https://github.com/flegare/pixel-block-chain>.

## Run locally

```bash
python -m http.server 8777
# open http://127.0.0.1:8777
```

Or just open `index.html` directly in a browser.
