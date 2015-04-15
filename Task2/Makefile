TEX = pdflatex -shell-escape
TEXOPTS = -jobname=task2
all : main.pdf
view : open main.pdf

main.pdf : main.tex tex/*.tex *.sty
	$(TEX) $(TEXOPTS) main.tex
	$(TEX) $(TEXOPTS) main.tex
