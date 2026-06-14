# Canopy

An editorial data-visualisation generator. Paste data (CSV / TSV / Excel / raw numbers), describe the insight you want to land, optionally set brand colours, and Canopy renders a polished, interactive chart — never a default bar / line / pie.

**Live:** https://justinthorpe59-source.github.io/canopy/

- Self-contained single HTML file — D3 and the hero image are inlined, so it works offline (aside from web fonts, which fall back to system fonts).
- Picks an unconventional chart form to fit the data and the brief: radial bars, slope, dot-matrix / waffle, beeswarm, connected scatter, dot strip, or layered ridge.
- Warm editorial aesthetic with per-project brand-colour overrides (each swatch opens a colour-picker popover), and one-click export — copy or download self-contained **HTML**, or download a true-vector **SVG** — for dropping charts into slides.
- "Try an example" cycles through several built-in datasets, each landing on a different chart form.
