# beamer-template
A beamer template for my pretty presentations

## Dependencies
Required packages: `minted`, `fontspec`, `graphicx`, `tabularx`.

Required programs: `pygments` and  `pygmentize` (for `minted`), `lualatex` (for UTF8 support and nice fonts).

Fonts: Roboto Slab and Tex Gyre Heros

## Build
For the PDF: `lualatex -shell-escape template.tex`

To set up the bibliography: `bibtex template`

## Useful tips
* `pygmentize -L styles` gives the list of styles availables for `minted`
* `pygmentize -L lexers` gives the list of languages availables for `minted`
* Minted documentation is [here](https://github.com/gpoore/minted/blob/master/source/minted.pdf)
* Update font cache in case fonts are not found: `luaotfload-tool --update`
* Beamer user guide: [here](http://ftp.math.purdue.edu/mirrors/ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf)
