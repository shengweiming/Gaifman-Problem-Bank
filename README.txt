Problems in Symbolic Logic
==========================
A TA recitation problem bank organized by the chapters and topics of
Haim Gaifman's A Course in Symbolic Logic.

The collection contains 55 exercises in nine chapters, selected and
consolidated from the recitation archive of Jamie Beardmore, Milo Beckman,
and Wei. Problem numbering restarts in each chapter.

Building
--------
Install a LaTeX distribution such as TeX Live or MacTeX, then run:

  latexmk -pdf main.tex

Alternatively, run pdflatex main.tex twice. The source is standalone;
all diagrams are included, and no external images or bibliography are needed.

Optional appendices
-------------------
The source catalogue, editorial notes, and selected solutions are hidden
by default. Near the top of main.tex:

  Change \showappendicesfalse to \showappendicestrue to show the source
  catalogue and editorial notes.

  Change \showsolutionsfalse to \showsolutionstrue to show the supplied
  solutions. These cover only the indicated exercises and parts.

Recompile after changing either option. The source catalogue credits the
43 original files. The textbook and original handouts are not included.
