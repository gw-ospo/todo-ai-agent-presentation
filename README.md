# How the GW OSPO Uses AI

A ~30 minute Quarto (reveal.js) talk on how the GW Open Source Program Office uses AI.
Built with the [gw-presentation](https://github.com/gw-ospo/gw-presentation) skill's brand rules
(palette, fonts, official chevron and star assets, one idea per slide).

## Structure

1. OSPO overview (3 slides)
2. Part 1: design skill and review process
3. Part 2: Quarto and AI (content vs. format, three benefits)
4. Part 3: other AI work (TAI, OFAI, pop-up AI museum)
5. Part 4: open source discovery & curation (ORB, OSPO Radar)

Speaker notes (press `S`) carry timings.

## Build

```bash
quarto render index.qmd   # writes a self-contained index.html
```

GitHub Pages: serve from the repository root on `main` (`.nojekyll` is included).

`_gw-assets.scss` is generated from the SVGs in `assets/` (inlined as base64 so the deck is self-contained).

## License

Code: see LICENSE. GW logos and graphic elements are not licensed for reuse; see the gw-presentation repo.
