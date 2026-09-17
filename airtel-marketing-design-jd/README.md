# Senior Manager, Marketing Design - Airtel

A single-page job description, styled after shadcn/ui primitives.

- `index.html`: the page. Open it in a browser; no build step, no dependencies. Inter loads from Google Fonts and falls back to the system sans stack offline.
- `Airtel-Senior-Manager-Marketing-Design.pdf`: A4 export with fonts embedded.

**Download PDF** in the header opens the browser print dialog against a dedicated A4 stylesheet (nav and theme toggle hidden, role details reflowed into a three-column strip under the title). Ctrl / ⌘ + P does the same.

The page follows the viewer's light or dark theme and the toggle overrides it.

## Airtel mark

The logo in the header is a hand-drawn SVG approximation, not the official asset: the mark lives in a single `<symbol id="airtel-mark">` at the end of the body, referenced by both the screen header and the print header. Replace that one path with the official SVG and both update.
