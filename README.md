another-latex-thesis-template
=============================

Template for a simple thesis or dissertation, for a Ph.D. or master's degree, in LaTeX.

**Online template on ShareLaTeX:**<br>
<https://www.sharelatex.com/templates/thesis/simple-thesis-dissertation>

**Compiled sample document:**<br>
[Thesis.pdf](https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Thesis.pdf)

**Sample pages (click to enlarge):**

<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-01.png" alt="Screenshot 01">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-02.png" alt="Screenshot 02">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-03.png" alt="Screenshot 03">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-04.png" alt="Screenshot 04">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-05.png" alt="Screenshot 05">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-06.png" alt="Screenshot 06">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-07.png" alt="Screenshot 07">
<img height="225" src="https://raw.githubusercontent.com/zachscrivena/another-latex-thesis-template/master/Miscellaneous/Screenshot-08.png" alt="Screenshot 08">

## Main Features

- Simple template that can be further customized or extended.
- Consistent style for figures and tables.
- Consistent style for mathematical theorems, definitions, lemmas, etc.
- Template document contains numerous examples.

## Overview

The main LaTeX source file is `Thesis.tex`; the compiled document is `Thesis.pdf`.

Instructions for compiling the document (TEX &rarr; DVI &rarr; PDF):

- **Method 1:** Use latexmk for fully automated document generation:
	- `latexmk -e "$dvipdf='dvipdfm %O -o %D %S'" -pdfdvi "Thesis.tex"`

- **Method 2:** Use latex, bibtex, and dvipdfm manually:
	- `latex "Thesis.tex"`
	- `bibtex "Thesis"`
	- `latex "Thesis.tex"` (run multiple times to resolve cross-references)
	- `dvipdfm "Thesis.dvi"`

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.
