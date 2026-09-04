# Early vs delayed introduction of progressive enteral feeding volumes — web bundle

Static, self-contained HTML. No build step, no server-side code, no external network
requests: all CSS is inlined in `index.html`, all images and data files are local and
referenced by relative path.

## Contents

```
index.html                  the full report (62 KB) — inlined CSS, 9 figures, 5 tables
figures/*.jpg               9 progressive JPEGs, up to 2000 px wide (2.3 MB total)
data/*.csv, *.txt           8 companion data files, linked from section 7
```

## Deploy

Copy the whole directory to the document root, preserving structure:

```sh
rsync -av --delete ./ user@server:/var/www/<path>/
```

Or on object storage (`index.html` must serve as the directory index):

```sh
aws s3 sync ./ s3://<bucket>/<prefix>/ --acl public-read
```

Nothing else is required. `index.html` opens directly from the filesystem too
(`file://`), which is useful for review before upload.

## Notes

- Figure JPEGs are converted from 300 dpi PNG masters, quality 95, chroma subsampling
  disabled — the forest plots are line art with small type, and subsampling introduces
  visible colour fringing on the confidence-interval whiskers. Each figure links to its
  full-size JPEG.
- Figures are placed at the end of the section that discusses them. Figure numbering
  follows the report's own scheme, so Figure 7 (funnel plot) appears after Figure 8
  (subgroup forest) in document order, matching sections 4.5 and 4.6.
- The Appendix renders Tables 1 to 3 as HTML from the companion CSVs so the document is
  readable in a browser without downloading anything. The CSVs remain the
  machine-readable record.
- Risk-of-bias markers in Appendix Table 2 carry the full judgement text as a `title`
  attribute (hover to read).
- Responsive at one breakpoint (900 px): the sidebar contents list becomes a two-column
  block above the text. A print stylesheet drops the sidebar and avoids breaking figures
  and tables across pages.
- Text is the version 2 manuscript, unmodified apart from one sentence in section 7
  describing the figure delivery format, and the addition of relative links on the
  companion filenames. No FEED1 content.

Built 2026-09-01.
