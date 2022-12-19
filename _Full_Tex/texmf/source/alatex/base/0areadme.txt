
				   
		      ALaTeX Distribution Guide
                      
			   21 January 1996
		      Matt Swift <swift@bu.edu>


WELCOME TO ALaTeX!

This file is a brief guide to the ALaTeX document preparation system,
which is a small but useful modification of the LaTeX document
preparation system.  You may produce a discussion of the goals of
ALaTeX by processing the file `metaclas.tex' with LaTeX.  The paper is
based on parts of the article "Modularity in LaTeX" by Matt Swift in
TUGboat vol. 16 no. 3.

ALaTeX is NOT part of the LaTeX distribution.  It is maintained
exclusively by Matt Swift <swift@bu.edu>, NOT by the LaTeX
maintainers.

The ALaTeX distribution will probably work with all LaTeX versions,
but it has been tested starting with the December 1995 release.  If a
change in the LaTeX kernel requires a change in ALaTeX that makes it
incompatible with earlier LaTeX kernels, I will increase the major
version number.  If I make an drop-in improvement to ALaTeX, I will
update the minor version number.

The ALaTeX version is displayed on the screen every time ALaTeX is
invoked with a reminder that ALaTeX is not standard LaTeX.

The file 00readme.txt in the LaTeX distribution contains information
about the LaTeX distribution.

Here is a brief description of some of the ALaTeX files:

 - ainstall.txt  describes how to install ALaTeX and its documentation.
 - metaclas.cfg  is the standard ALaTeX metaclass.
 - alatex.tex    documents ALaTeX and its standard metaclass.
 - alatex.ltx    is a patch to the LaTeX kernel.
 - amanifst.txt  lists all the files in the ALaTeX distribution with
                 one line of information about their contents.
 - abugs.txt     describes how to submit a bug report for ALaTeX.
 - COPYING       is a copy of the GNU General Public License.
 - Makefile      is a Unix makefile for building and installing ALaTeX on
                 Unix systems.


COPYRIGHT
=========

The ALaTeX files in this distribution are copyright 1995 Matt Swift
<swift@bu.edu>.  All rights reserved.


WARRANTY
========

There is no warranty for ALaTeX.  See the file COPYING for details.


DISTRIBUTION CONDITIONS
=======================

ALaTeX may be distributed under the conditions of the GNU General
Public License, which is in the file COPYING.


ACKNOWLEDGMENT
==============

The ALaTeX format that the files in this distribution will generate
represents a VERY small modification of the LaTeX format, whose source
files are copyright 1993-1995 the LaTeX3 project and the individual
authors:

   Leslie Lamport
   Johannes Braams 
   David Carlisle
   Alan Jeffrey
   Frank Mittelbach
   Chris Rowley
   Rainer Schoepf

The authors of the original LaTeX files deserve all of the credit for
the functionality of ALaTeX.  The author of ALaTeX added only the
smallest of contributions, and thanks the original authors for writing
the files and for distributing them under conditions which allowed him
to legally make and distribute his addition.
