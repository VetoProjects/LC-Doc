all: doc

doc:
	latex compile.tex
	latex compile.tex
	latex compile.tex
	dvips compile.dvi
	ps2pdf compile.ps
	mv compile.pdf Dokumentation.pdf
	rm compile.toc compile.dvi compile.log compile.ps compile.out *.aux
