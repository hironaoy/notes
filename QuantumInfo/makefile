main.pdf: main.dvi
	dvipdfmx main.dvi

main.dvi: main.tex
	platex main.tex

clean:
	rm -rf main.aux main.dvi main.log
