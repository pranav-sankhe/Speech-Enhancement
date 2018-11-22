all: Thesis.pdf

Thesis.pdf: Thesis.tex
	pdflatex -shell-escape Thesis.tex

.PHONY: clean
clean:
	$(RM) Thesis.pdf \
Thesis.aux \
Thesis.bbl \
Thesis.blg \
Thesis.log \
Thesis.out \
Thesis.pdf \
Thesis.tex~
