TEX = pdflatex
BIBTEX = bibtex8
BIBTEX_OPTIONS = -c utf8cyrillic.csf

all : main.pdf

main.pdf : main.tex tex/*.tex *.sty *.bib 
	$(TEX) main.tex
	$(BIBTEX) $(BIBTEX_OPTIONS) main.aux
	$(TEX) main.tex
	$(TEX) main.tex
