FILE	= plantillatfg 

all:
	pdflatex  $(FILE).tex
	bibtex $(FILE)
	pdflatex  $(FILE).tex
	pdflatex  $(FILE).tex

clean:
	rm -f *.log *.aux *.dvi *.toc *.out *.bbl *.blg *.lof *.lot
