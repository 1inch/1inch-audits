# AGENTS.md

## Cursor Cloud specific instructions

This repository (`1inch/1inch-audits`) is a **static document archive**, not a software application.
Its content is:

- `README.md` — an index that links to the audit report PDFs.
- 145 PDF audit reports grouped into per-protocol folders (e.g. `Aggregation Protocol V2/`, `Cross-chain Protocol/`).
- `LICENSE.md`, `.gitignore`, and two brand SVGs under `.github/`.

There is **no application code, package manifest, build system, test suite, or linter** anywhere in the repo,
so there is nothing to install, build, lint, or test. Do not add a toolchain or CI unless explicitly asked.

"Development" here means editing `README.md` and adding/removing/renaming PDF files. When adding a report,
place the PDF in the matching protocol folder and add a corresponding link under the right heading in `README.md`.

### Previewing the archive
The repo has no dev server of its own. To browse it as it is consumed (folders + PDFs), serve the directory with
Python's stdlib server (already available, no install) and open it in a browser:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`, click into a protocol folder, and click a PDF to render it in the browser's
PDF viewer. `README.md` links point at GitHub `raw`/`blob` URLs, so those specific links only resolve on GitHub,
not on the local static server (browse the folders directly instead).
