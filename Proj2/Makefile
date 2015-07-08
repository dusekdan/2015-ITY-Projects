file = proj2

make: $(file).tex
	latex $(file).tex
	dvips -t a4 $(file).dvi
	ps2pdf $(file).ps
	latex $(file).tex #2x preklad
	dvips -t a4 $(file).dvi
	ps2pdf $(file).ps