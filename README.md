# Many-Body Quantum Magic — class presentation

Beamer slides on Liu & Winter, *Many-body quantum magic* (arXiv:2010.13817).

## Who edits what

| File | Content | Owner |
|---|---|---|
| `sections/01-motivation.tex` | Roadmap, motivation & background | Philipp |
| `sections/02-measuring-magic.tex` | Dmin, Dmax, LR, sandwich | Clara |
| `sections/03-bounds.tex` | Theorems 1–4 | Diallo |
| `sections/04-hypergraph-boolean.tex` | Hypergraph states & Boolean functions | Clara |
| `sections/05-pauli-mbqc.tex` | Pauli MBQC, Theorem 5, Corollary 6 | Diallo |
| `sections/06-spt-phases.tex` | Magic in SPT phases | Philipp |
| `sections/07-conclusions.tex` | Conclusions | shared |
| `sections/99-backup.tex` | Backup slides | shared |
| `preamble.tex` | Theme, packages, colours, macros | ask first |

Edit only your own file where possible, so changes never collide. Put images in `figures/`.

## Getting the PDF

Every push to `main` compiles the slides automatically (GitHub Actions).
The current PDF is always under **Releases → "Latest slides"** → `main.pdf`.

## Editing

**In the browser (no install):** open a file on GitHub → pencil icon → edit → *Commit changes*. Wait ~1 min for the PDF to rebuild.

**Locally (recommended):**
```bash
git clone <repo-url>
cd many-body-magic-slides
latexmk -pdf main.tex        # needs a TeX distribution (MacTeX / TeX Live / MiKTeX)
```
Before starting work: `git pull`. When done: `git add -A && git commit -m "..." && git push`.

**With Overleaf (each person on their own free account):** Overleaf → New Project → Upload Project → upload a zip of this repo. Edit there, then download your section file and commit it here. (Direct Overleaf ↔ GitHub sync needs a paid Overleaf plan.)
