$Id: README, v0.1a 2009/07/17 00:04:00 ttitz $

----------------------------------------------------------------
authoryear-icomp-tt - author-year style with compact multiple-
    reference-citations and ibidem mechanism
Maintained by Thomas Titz
E-mail: thomas.titz@chello.at
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt
----------------------------------------------------------------
  
Description:

This package provides a citation scheme that combines the
features of the styles authoryear-comp (omission of recurring
author/year in multiple-reference-citations) and authoryear-ibid
(replacement of repeated citations by the abbreviation ibidem).
The implementation relies heavily on unmodified biblatex macros,
and no attempt has been made to add further features not present
in core biblatex.

This package requires biblatex v0.8e or later.

Installation:
 
Extract the zip archive to the <TEXMFLOCAL> directory of your
system. Don't forget to update the file hash tables after
installing the files.

Usage:

Load the style as the biblatex standard styles:

  \usepackage[style=authoryear-icomp-tt]{biblatex}

Revision history:

v0.1  Initial public release (for biblatex v0.8e)
v0.1a Bugfix: Preamble option ibidpage should work now
