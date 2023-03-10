                     The NICETEXT bundle

     (c) 2009 2010 Uwe Lueck http://contact-ednotes.sty.de.vu


                     == General Idea ==

The NICETEXT bundle supports "minimal" markup syntax for rather 
simple kinds of text. The code you type should show little more 
characters than are printed, though you get LaTeX quality. We try 
to do away with backslashes, technical terms, and curly braces 
(which also are so clumsy to type on PC keyboards). 

Main focus is easy documentation of LaTeX packages. Preprocessing 
by Perl or so is replaced by TeX macros (reviving/generalizing the 
'docstrip' idea), including expandable, safe, correct string 
substitution and typographical enhancements of plain text for 
LaTeX input. 


                       == Packages ==

'wiki.sty' addresses general kinds of texts. 'niceverb.sty' is 
made for documenting LaTeX packages. 'niceverb.sty' especially 
offers [almost-]WYSIWIG for meta-variables (macro arguments) and 
for referring to commands (and their syntax) in footnotes, 
section titles etc. E.g., to get the syntax description

                 \foo[<opt-arg>]{<mand-arg>}
you just type 
                 \foo[<opt-arg>]{<mand-arg>}
!-)

'fifinddo.sty' provides basic setup for text filtering, especially 
string substitution. 'makedoc.sty' extends it to provide a simple 
script language for transforming plain text package files into LaTeX 
input files [manual!?]. One LaTeX run can perform preprocessing and 
typesetting. 


                      == Comparisons ==

One source of inspiration is the markup syntax of editing Wikipedia 
pages. 'wiki.sty' of the bundle offers something similar as a LaTeX 
front-end for italics, boldface, sectioning, and certain list-like 
environments. This is also similar to 'easylatex', 

               http://www.ctan.org/pkg/easylatex

which is more powerful and uses Perl. NICETEXT, by contrast, consists 
just of LaTeX packages, working on any TeX installation [!? note 
restrictions in 'fifinddo.pdf']. Cf. also preprocessor packages 
'txt2tex' and 'txt2latex'. 

Regarding "self-documentation," there is a difference to current 
`\DocInput', similar ideas are in 'gmdoc' and 'lineno.sty', 
see 'niceverb.pdf' and 'makedoc.pdf'. Standard 'doc.sty' and 
'contrib' extensions of it are rather avoided.

There are several *LaTeX macro* packages for processing text or 
databases or for editing TeX's input stream while typesetting 
-- see 'fifinddo.pdf'. What seems to be new here is 
*expandable string substitution* and safe, correct detection of 
substrings -- discussed in 'fifinddo.pdf'. 


                     == Documentation ==

'fifinddo.pdf' describes 'fifinddo.sty', typeset from 'fifinddo.tex'. 
'makedoc.pdf' describes 'makedoc.sty', typeset from 'makedoc.tex'. 
'mdoccheat.pdf' is a list of script commands, typeset from 'mdocchea.tex'.
'niceverb.pdf' describes 'niceverb.sty', typeset from 'niceverb.tex'. 
Typesetting them anew (for customizing printout) requires 
'makedoc.cfg', 'mdoccorr.cfg', and the *.sty files.

'wikicheat.pdf' is a one-page manual of 'wiki.sty'. The file 
'wiki.sty' contains additional documentation as plain text. 
Note that certain features must be activated by commands in the 
document environment.


                   == Templates/Dialogue ==

txt to TeX functionality through \MakeDocCorrectHook can be tried 
and applied with templates `fdtxttex.tpl' and `makedoc.tpl' and in 
a dialogue started by running `fdtxttex.tex'.

`substr.tex' should typeset the version of Harald Harders' 
`substr.sty' next at your TeX installation. `arseneau.tex' 
should typeset documentation of a few packages by Donald Arseneau.
My results are `substr.pdf' and `arseneau.pdf'.


                       == Required ==

`makedoc.sty' requires the `moreverb' package from 

    CTAN:/macros/latex/contrib/moreverb


                        == License ==

Copying, distributing, modifying, using the files of the `nicetext' 
bundle are allowed under the terms of the LaTeX Project Public 
License, either version 1.3a or any later version, the latest version 
is at 

    http://www.latex-project.org/lppl.txt

There is NO WARRANTY, and you must CARE indeed with `fifinddo' and
`makedoc', they will OVERWRITE existing files without warning because 
their main purpose is updating. 

The bundle is AUTHOR-MAINTAINED in the sense of the LPPL.

Copyright (C) 2009, 2010 Uwe Lueck, 

    http://www.contact-ednotes.sty.de.vu 

Please report bugs, problems, and suggestions via the previous web 
form. 


               ________________________________
               [This file 2010/04/05 Uwe Lueck]
