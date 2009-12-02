all:
	sed -i -e 's/176mm/196mm/' opensourcepress.sty
	pdflatex gentoo.tex
	pdflatex gentoo.tex
	makeindex gentoo.idx -o index.tex
	pdflatex gentoo.tex
	sed -i -e 's/196mm/176mm/' opensourcepress.sty

clean:
	rm -f *.log *.aux *.pdf index.tex *.ilg *.idx *.toc
