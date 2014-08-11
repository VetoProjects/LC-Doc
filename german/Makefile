all: doc

doc:
	pdflatex -shell-escape compile.tex 2&> /dev/null
	bibtex compile.aux > /dev/null
	pdflatex -shell-escape compile.tex 2&> /dev/null
	pdflatex -shell-escape compile.tex 2&> /dev/null
	mv compile.pdf Dokumentation.pdf
	make clean

make clean:
	rm compile-* compile.b* compile.aux compile.log compile.out compile.toc
