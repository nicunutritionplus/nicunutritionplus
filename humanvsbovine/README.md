# Human milk-derived vs bovine milk-derived fortifiers — systematic review

Standalone HTML version of `review.docx`: a systematic review and meta-analysis of 7 randomised trials (920 infants) comparing human milk-derived and bovine milk-derived fortifiers in preterm infants, prepared following Cochrane methods and reported per PRISMA 2020.

## Contents

```
index.html           the review (self-contained; no build step)
assets/css/style.css  stylesheet
assets/img/           PRISMA flow diagram, risk-of-bias figure, and 9 forest plots
```

## Viewing

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Publishing on GitHub Pages

Push this folder to a repository and enable Pages under **Settings → Pages** (source: the branch containing these files, folder `/`, or `/review` if the repo has other content alongside it).

## Notes on the conversion

- Converted directly from the `.docx` XML (paragraphs, headings, tables and embedded images), not from a PDF or text export, so wording and numbers match the original exactly.
- The 11 embedded figures were re-encoded as optimized PNGs (adaptive palette, resized to a 1900px-wide max) to cut total image weight from about 3.3 MB to under 1 MB with no visible loss, since all of them are flat-color charts and text.
- `≥` replaced the document's literal `>=` for readability; nothing else in the wording was changed.
