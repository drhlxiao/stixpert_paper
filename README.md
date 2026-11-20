# StiXpert manuscript

This directory contains a standalone copy of the Elsevier LaTeX manuscript.

## Build

With a LaTeX distribution that includes `latexmk`, run from this directory:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error manuscript.tex
```

The manuscript source is `manuscript.tex` and `mainText.tex`; references are in
`bibsample.bib`. The Elsevier class and numeric-name bibliography style are
included locally. The architecture figure is included as
`figures/stixpert-architecture.pdf`; its original editable SVG is also provided
as `figures/stixpert-diagram.svg`.
