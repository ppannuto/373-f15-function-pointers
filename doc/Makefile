all: assignment.pdf to_submit.pdf

assignment.pdf:	assignment.tex
	latexmk -pdf assignment.tex

to_submit.pdf: to_submit.tex
	latexmk -pdf to_submit.tex

clean:
	rm -f assignment.pdf assignment.aux assignment.log assignment.out
	rm -f to_submit.pdf to_submit.aux to_submit.log to_submit.out
	rm -f *.dvi *.fls *.fdb_latexmk

.PHONY: all clean
