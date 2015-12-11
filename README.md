# Drinks menu

## 1. Generate graphics
For each .tex file named `deco-*.tex`, compile it with XeLaTeX.  This should generate a .pdf file containing the graphic.  The picture that each `psvectorian` code can be seen in [psvectorian.pdf](), copied in this repository.

For example,
```tex
\psvectorian{102}
```
will generate the following image:
![psvectorian lobster](lobster.png)

## 2. Generate document
Compile `drinks.tex` with pdfLatex.