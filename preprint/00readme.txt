Preprint Collection:					(April 2001)
~~~~~~~~~~~~~~~~~~~~
This directory contains some packages written by Patrick W. Daly.  The
primary distribution site is:

http://www.linmpi.mpg.de/english/services/software/latex/localtex/localltx.html

I (Arash Esbati) just mentioned balance.sty in comp.text.tex, was invited
to put in on CTAN, asked Patrick W. Daly for permission, wrote this readme
for your convenience and made a CTAN submission.


Legal stuff:
~~~~~~~~~~~~~~~~~~~~
The copyright holder of these packages is Patrick W. Daly.  They can be
redistributed and/or modified under the terms of the LaTeX Project Public
License Distributed from CTAN archives in directory
macros/latex/base/lppl.txt; either version 1 of the License, or any later
version.


Important note:
~~~~~~~~~~~~~~~~~~~~
Unfortunatly, the author of these packages doesn't have the time for
further development, bug fixes, "wishes" etc.  Hence, they are provided
"as is".  If you run into problems, you are on your own.


Brief description:
~~~~~~~~~~~~~~~~~~~~
1. appendix.sty:  (version 2.1 from 1999/02/23)
   Adding this package redefines \appendix so that main counters for
   figures, tables, equations are subnumbered under the appendix.  The
   plate counter is also subnumbered.  A \noappendix command is included so
   that things like bibliographies may be called after the appendix with
   \section*.  This package is only useful with article documentclass for
   obvious reasons.

2. authblk.sty:   (version 1.3 from 2001/02/27)
   A LaTeX2e package to redefine the \author command to work as normal or
   to allow a footnote style of author/affiliation input.

3. balance.sty:   (version 4.3 from 1999/02/23)
   When writing a document with LaTeX two-column mode, the columns on the
   last page, or those before a \cleardoublepage command, will be of
   unequal height.  balance.sty solves this problem by modifying the output
   routines in two-column mode.

4. figcaps.sty:   (version 4.7 from 1999/02/23)
   This package allows the figure captions to be collected throughout the
   paper and printed on a separate page at the end.  The figures themselves
   will not appear in the text.  This is for purposes of a manuscript for
   submission.  Similarly, tables are not printed in the text, but are
   outputted at the end, after the figure captions.  This package may
   optionally be used with the longtable environment defined in the package
   of the same name.

5. fullpage.sty:  (version 1.1 from 1999/02/23)
   This package sets all 4 margins to be either 1 inch or 1.5 cm, and
   specifies the page style.

6. sublabel.sty   (version 4.5 from 1999/02/23)
   The macros in this package allow all counters to be subnumbered, as for
   example 4a, 4b, 4c, simply by bracketting the objects to be so numbered
   with appropriate on/off commands.  They will work with any user-defined
   counters too.


Installation:
~~~~~~~~~~~~~~~~~~~~
Just run LaTeX on (package).ins, which generates (package).sty.  If you
want the documentation as a dvi, run LaTeX on (package).dtx, otherwise use
the provided formats.  Move the .sty-files to a directory where LaTeX looks
for the input files.  Update your file name database and you're done.
Check your local guide for more Information.


Happy TeXing!
	Arash Esbati (esbati@gmx.de)