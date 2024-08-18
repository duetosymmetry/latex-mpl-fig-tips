[![LaTeX build](../../actions/workflows/pdflatex.yml/badge.svg)](../../actions/workflows/pdflatex.yml)
[![Latest build of the paper](https://img.shields.io/badge/PDF-latest-orange.svg?style=flat)](../gh-action-result/pdflatex/latex-mpl-fig-tips.pdf)

This is a simple revtex LaTeX template (using JHEP.bst), and this repo uses github actions to automatically build the latest PDF. The result is linked above.

If you use this repo template, GitHub will by default not enable
actions to be able to push back to the repo, which is needed to store
the PDF (in an orphan branch). To enable them, go to your repo's
settings, go to Actions, then down to Workflow permissions, and enable
'Read and write permissions'.
