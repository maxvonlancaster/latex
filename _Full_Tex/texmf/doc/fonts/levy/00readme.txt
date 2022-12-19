This directory contains materials for using TeX to typeset Greek
text using Sylvio Levy's fonts. The following files are present:

00readme.txt        This file.
a.mf                MF code for alpha-based characters
b.mf                MF code for beta-based characters
d.mf                MF code for delta-based characters
digits.mf           MF code for numerals
e.mf                MF code for epsilon-based characters
f.mf                MF code for phi-based characters
g.mf                MF code for gamma-based characters
gen_acc.mf          MF code for accents
gen_sigma.mf        MF code for sigma compounds
graccent.mf         MF code for accents
grbase.mf           MF code for base Greek macros
grbld8.mf           Parameter file for 8pt Bold
grbld9.mf           Parameter file for 9pt Bold
grbld10.mf          Parameter file for 10pt Bold
greek.mf            Driver file for Greek font
greekhist.tex       History of Greek typesetting and info on
                     these fonts
greekmacros.tex     Macros to use Greek fonts.
greekuse.tex        Instructions on using the fonts.
grinstall.tex       Instructions on installing the fonts.
grpunct.mf          MF code for punctuation
grreg8.mf           Parameter file for 8pt "Roman"
grreg9.mf           Parameter file for 9pt "Roman"
grreg10.mf          Parameter file for 10pt "Roman"
grtestfont.tex      Testing TeX file for Greek (analagous to
                     testfont.tex)
grtt10.mf           Parameter file for 10pt Typewriter
h.mf                MF code for eta-based characters
i.mf                MF code for iota-based characters
j.mf                MF code for theta-based characters
k.mf                MF code for kappa-based characters
l.mf                MF code for lambda-based characters
lig.mf              MF code for ligatures
lower.mf            Driver file for lower case Greek letters
m.mf                MF code for mu-based characters
makeall.            Shell script to make all fonts
makefont.           Shell script to generate a font.
modes.mf            Mode definitions
n.mf                MF code for nu-based characters
o.mf                MF code for omicron-based characters
p.mf                MF code for pi-based characters
q.mf                MF code for chi-based characters
r.mf                MF code for rho-based characters 
s.mf                MF code for sigma-based characters
t.mf                MF code for tau-based characters
testfont.           Shell script to test fonts.
todo.txt            List of improvements to be made to the fonts.
u.mf                MF code for upsilon-based characters.
upper.mf            MF code for upper case characters
w.mf                MF code for omega-based characters
x.mf                MF code for xi-based characters
y.mf                MF code for psi-based characters
z.mf                MF code for zeta-based characters

Copyright (C) 1987 Princeton University
     
These fonts by Silvio Levy are partly based on Don Knuth's
Computer Modern family of fonts.  They are distributed WITHOUT
ANY WARRANTY, express or implied. Please send comments,
suggestions, etc. to levy@princeton.edu

IMPORTANT NOTE:
     
These fonts make use of the 256-character capabilities of gf
format. They cannot be converted to the obsolete PXL format which
allows only 128 characters. If you are still using PXL format
drivers, it is time to convert. If you are using a gf format
driver with only 128 character capacity, you are missing
something. See doc/install.tex.
     
Metafont must have |max_in_open| increased (to 10) to compile
these fonts as they stand. The appropriate change has been added
to the change files on the UnixTeX distribution. If you're
getting these fonts other than from the TeX distribution, and if
you don't have access to Metafont source, you'll have to merge
some files before you attempt compilation:
     
   In src/s.mf, replace the line readfrom("gen_sigma") by the
     contents of src/gen_sigma.mf.
   In src/lower.mf, replace each line by the contents of the
     corresponding file; for instance, replace readfrom("a") by
     the contents of src/a.mf.
   In greek.mf, right after the line that says ``font_setup''
     insert the lines
     
   readfrom("gen_acc");
   readfrom("gen_sigma");

HMC:
At HMC a couple of modifications have been made to the MF files:
   
   The definition of readfrom has been changed so that no
     directory information is present.
   accent.mf has been renamed graccent.mf and punct.mf has been
     renamed grpunct.mf to prevent conflicts with CM files.
