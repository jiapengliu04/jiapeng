# jiapengliu1.github.io

## Moduli theory paper

This repository includes a LaTeX manuscript, **A Working Introduction to Moduli Theory: A Hundred-Page Style Manuscript of Definitions, Theorems, Examples, and Exercises**.

The paper is located at [`papers/moduli_theory_hundred_page_notes.tex`](papers/moduli_theory_hundred_page_notes.tex). It is organized as 100 page-like sheets, each ending with `\clearpage`, so compiling the document produces a manuscript of at least 100 pages including front matter and appendices.

To build locally, run:

```bash
pdflatex -interaction=nonstopmode papers/moduli_theory_hundred_page_notes.tex
pdflatex -interaction=nonstopmode papers/moduli_theory_hundred_page_notes.tex
```
