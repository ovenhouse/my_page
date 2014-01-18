all: quiz1.pdf softclean


quiz1.pdf: src/quiz1.tex
	pdflatex src/quiz1.tex

softclean:
	rm -f *.log *.aux

hardclean: softclean
	rm *.pdf
