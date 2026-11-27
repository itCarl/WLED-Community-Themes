# Xmas Red

Deep candy red surfaces, fir green top and bottom bars, white text and a white frame around the selected entry.

Santa hats sit on the tab icons, each one a little different. Includes the shared fixes for small
screens: wide lists, full-width preset names and full-width segment sliders.

| Desktop | Mobile |
| --- | --- |
| <img src="desktop.png" width="560" alt="Xmas Red on desktop"> | <img src="mobile.png" width="200" alt="Xmas Red on mobile"> |

## Colours

<img src="palette.png" width="126" alt="colours">

| Role | Colour |
| --- | --- |
| Background | `#2a070b` |
| List entries | `#4a0f16` |
| Bars | `#14462a` |
| Accent | `#ffffff` |
| Text | `#f2dede` |

## Files

- [`theme-xmas-red.css`](theme-xmas-red.css) - ready to upload
- [`theme-xmas-red.scss`](theme-xmas-red.scss) - source; the colours are the `$x-…` variables at the top

Don't want the hats? Remove `@import 'xmas/santa-hats';` from the `.scss` and run `npm run dev`.

## Install

Upload `theme-xmas-red.css` as `/skin.css` and enable **Config → User Interface → Enable custom CSS**
(see the main [README](../../README.md#installation)).
