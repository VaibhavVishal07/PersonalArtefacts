# Senior Manager, Marketing Design - Airtel

A one-page job description. Reads as a document on screen and prints to a single A4 sheet.

- `index.html`: the page. Open it in a browser; no build step, no dependencies.
- `Airtel-Senior-Manager-Marketing-Design.pdf`: the A4 export, one page, fonts embedded.

**Download PDF** in the top right opens the print dialog against a dedicated print stylesheet: the buttons drop out, type scales to points, and the whole thing is tuned to land on one page. Ctrl / Cmd + P does the same. The page follows the viewer's light or dark theme; the toggle overrides it.

## Airtel logo

The mark is a hand-drawn SVG approximation, not the official asset, and the wordmark is set in Quicksand rather than Airtel's own face. Replace both when you have the real files:

- the mark is the single `<path>` inside `<span class="logo">`
- the wordmark is the `<span class="word">` beside it

Sizes for screen and print are set on `.logo svg` and `.logo .word` in their respective blocks.
