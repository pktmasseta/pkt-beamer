PKT Mass Eta - Beamer Presentation Template
==================================

LaTeX Beamer presentation template derived from Andreas Kloeckner's brown-beamer template:

http://mathema.tician.de/software/brown-beamer

Dependencies:
-------------
* latex-beamer class 3.0.7 (http://latex-beamer.sourceforge.net)
* texlive-latex 2008+ (http://www.tug.org/texlive/)

Install:
--------
Install is simply downloading the code from github. Here we install pkt-beamer to $HOME/pkt-beamer::

    $ cd $HOME
    $ git clone https://github.com/pktmasseta/pkt-beamer.git

Generating the presentation:
----------------------------
1. Customize pkt-beamer/slides.tex to your liking::

    $ vim $HOME/pkt-beamer/slides.tex

2. Run pdflatex to generate a presentation PDF (twice if needed)::

    $ pdflatex slides.tex

3. You can then view the resulting pdf, named slides.pdf::

    $ evince slides.pdf
