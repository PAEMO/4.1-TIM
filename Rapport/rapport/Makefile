TEX=$(shell pwd)/../ressources//:$(shell kpsewhich --expand-var='$$TEXINPUTS')

all:
	TEXINPUTS=$(TEX) pdflatex rapport.tex
	TEXINPUTS=$(TEX) pdflatex rapport.tex
	rm -f *.aux *.cb *.cb2 *.log *.toc *.out *.lof *.lot

clean:
	rm -f rapport.pdf
	rm -f *.aux *.cb *.cb2 *.log *.toc *.out *.lof *.lot
