# pdflatex-output
A TeXShop Engine script that hides all auxiliary TeX files in a hidden subdirectory called `.texaux`
  in the current working directory.  Only the `.tex` and `.pdf` files are kept visible in the 
  working directory.

## To install and run in TeXShop
Move the file `pdflatex-output.engine` to the directory `~/Library/TeXShop/Engines`.
In the TeXShop editor, change the current engine in the dropdown menu next to the
`Typeset` button to `pdflatex-output`.  To use `pdflatex-output` as the default engine,
open `TeXShop > Preferences > Typesetting` and change the `Default Command` to
`pdflatex-output`.
