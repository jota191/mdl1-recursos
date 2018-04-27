
LATEX = pdflatex -shell-escape -interaction=nonstopmode -file-line-error
TEX = tex

2018-simu:
	$(LATEX) 2018-1-simu.tex

2018-simu-accmod:
	$(LATEX) --jobname=2018-simu-accmod \
	"\def\accmod{1} \input{2018-1-simu.tex}"


2018-1:
	$(LATEX) 2018-1-parcial.tex

2018-accmod:
	$(LATEX) --jobname=2018-1-accmod \
	"\def\accmod{1} \input{2018-1-parcial.tex}"

2017-1:
	$(TEX) 2017-1-parcial.tex

2017-simu:
	$(TEX) 2017-1-simu.tex

2017-2:
	$(TEX) 2017-2-parcial.tex


.PHONY: clean
clean:
	rm *log *aux *~ *pdf *dvi
