README for the tcldoc package and document class.

The tcldoc package defines a couple of environments and commands 
for documenting Tcl (Tool Command Language) source code in .dtx-style 
documented source files, much like what the doc package does for TeX 
source code. The tcldoc class is analogous to the ltxdoc document 
class -- it loads the package to gain the basic functionality and 
changes some layout parameters to values that are more suitable for 
this kind of document.

Experienced doc users should find most of tcldoc's functionality 
familiar. For those who are not experienced doc users, the tcldoc 
documentation contains an elementary introduction to the .dtx-file 
style of literate programming and to using the docstrip program for
Tcl code.

The tcldoc package builds on the doc and xdoc2 packages, which can be 
found in any standard LaTeX installation and the CTAN directory 
macros/latex/exptl/xdoc/, respectively. 


The files in this directory are:

README.txt    - this file
tcldoc.dtx    - the source for the tcldoc package and class
tcldoc.ins    - the docstrip installation script for the tcldoc 
                package and class

dtxload.dtx   - a tcldoc demonstration file. It contains the 
                documented sources for dtxload, which is a package 
                for the text editor Alpha that defines a command
                for extracting Tcl code from a .dtx file and sending 
                that code to a Tcl interpreter for evaluation.
dtxload.ins   - the docstrip installation script for dtxload
pstokens.dtx  - another tcldoc demonstration file. It contains some 
                Tcl procedures for reading and writing a text file 
                as a stream of postscript tokens. N.B.: It is not in 
                it current state ready for use, but simply provided
                as an example.

2000/12/20,
Lars Hellstr\"om



