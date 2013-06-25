all:
	latex draft.tex
	bibtex draft
	latex draft.tex
	latex draft.tex
#	dvipdfmx draft.dvi
	dvips -t letter -o draft.ps draft.dvi
	ps2pdf draft.ps

clean:
	rm -fr *~ *.log *.aux *.bbl *.blg *.dvi
