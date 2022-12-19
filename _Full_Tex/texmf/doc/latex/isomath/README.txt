isomath README
~~~~~~~~~~~~~~

:Date:      2010-08-23
:Copyright: © 2008, 2010 Günter Milde <milde@users.berlios.de>

:Licence:   This work may be distributed and/or modified under the
            conditions of the `LaTeX Project Public License`_, either
            version 1.3 of this license or (at your option) any later version.

:Abstract:  The isomath package enables formatting Greek and Latin
            letters as symbols for vectors, matrices, and tensors
            in the typefaces recommended for scientific papers
            by the International Standard ISO 31.

Files
=====

====================  =================================
README.txt            Requirements, Installation, Usage
README.html           browser friendly README
                      
isomath.sty           literate source (the actual LaTeX package)
isomath.sty.txt       literate source (text version)
isomath.sty.html      literate source (HTML)
                      
isomathtxt       user documentation (source)
isomathhtml      user documentation (HTML)
isomathpdf       user documentation (PDF)
                      
isomath-test.tex      Test example (source)
isomath-test.pdf      Test example (PDF output)
====================  =================================

The bidirectional text <-> code converter PyLit_ can convert between
``isomath.sty`` and ``isomath.sty.txt``.

The Python Docutils_ and pdflatex were used to generate the HTML and PDF
documentation from the reStructuredText_ sources.


Requirements
============

This package builds on and extends fixmath_ by Walter Schmidt.
It also requires kvoptions_.

The cmbright_ package is recommended for *sans-serif italic* and *sans-serif
bold italic* fonts matching with Computer Modern and derivatives.

All required packages are part of TeXLive and MikTeX.

Installation
============

* Unpack isomath.zip (preferabely in a TDS_ documentation folder).

* Make sure LaTeX can find isomath.sty:

  Copy/Move/Link it to a suitable place in the TDS_ and run ``texhash``
  or place it in the current working directory (e.g. for testing).


Usage
=====

::

  \usepackage{isomath}

Option description, more examples and usage hints are in the user
documentation.

.. References
   ==========

.. _LaTeX Project Public License: http://www.latex-project.org/lppl.txt
.. _pylit: http://pylit.berlios.de
.. _reStructuredText: http://docutils.sourceforge.net/rst.html
.. _docutils: http://docutils.sourceforge.net/rst.html

.. _cmbright: http://dante.ctan.org/CTAN/help/Catalogue/entries/cmbright.html
.. _fixmath: http://dante.ctan.org/CTAN/help/Catalogue/entries/fixmath.html
.. _kvoptions: http://dante.ctan.org/CTAN/help/Catalogue/entries/kvoptions.html

.. _TDS: http://www.tex.ac.uk/cgi-bin/texfaq2html?label=tds
