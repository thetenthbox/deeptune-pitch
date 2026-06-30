# Deeptune Pitch — RL Environments for Finance

A two-page technical report / pitch document, authored as a single self-contained HTML file.

- **Page 1** — Cover: *RL Environments for Finance*.
- **Page 2** — *The Research Engine*: how the multi-agent research engine works, with an architecture diagram.

## Files

- `index.html` — the full document (both pages). Open in any browser.
- `fonts/` — CMU Serif (Computer Modern) web fonts used by the diagram.
- `deeptune-pitch.pdf` — pre-rendered US-Letter PDF.

## Regenerating the PDF

Rendered with headless Chrome:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --disable-gpu --no-pdf-header-footer \
  --print-to-pdf=deeptune-pitch.pdf --virtual-time-budget=4000 \
  "file://$PWD/index.html"
```
