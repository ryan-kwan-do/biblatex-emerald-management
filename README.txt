$Id: README,v 0.1.1 2017/03/11 BH alpha $

Please note that this package is in alpha stage and released for
testing only. If you see an error, please let me know at hello@ryanarmstrong.me (but be nice!)

Description:
A reference package for the International Journal of Productivity and Performance Management and other management journals under Emerald publishing

Installation:

Copy the .cbx and .bbx files to:

	<TEXMFLOCAL>/tex/latex/biblatex-contrib/biblatex-emerald-management

where <TEXMFLOCAL> denotes the root of the local TeX installation. Don't forget to update
the file hash tables after installing the files.

Journals include, and the associated style to reference:
 1) International Journal of Productivity and Performance Management (IJPPM)

Usage:

Call the style you would like to use in the preamble along with biblatex
		\usepackage[style=biblatex-IJPPM]{biblatex}

Note that this package only addresses citations and references. The journals also include requirements for headings, notes, figures

This material is subject to the LaTeX Project Public License. See http://www.ctan.org/tex-archive/help/Catalogue/licenses.lppl.html for the details of that license.
