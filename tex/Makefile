driver = HEPML.tex
output_file = $(basename $(driver)).pdf
tex_source = $(wildcard *.tex)
#image_source = $(wildcard Images/*.pdf) $(wildcard Images/*.jpg) $(wildcard Images/*.png)
bib_source = $(wildcard *.bib)
REFERENCES = true
TEX=xelatex

all: document

document: $(driver) $(tex_source) $(bib_source)
	$(TEX) $(driver)
	$(TEX) $(driver)
	if [ "$(REFERENCES)" = true ]; then bibtex $(basename $(driver)); $(TEX) $(driver); $(TEX) $(driver); fi

clean:
	\rm -f *~ *.aux *.bbl *.blg *.dvi *.idx *.lof *.log *.lot *.toc *.glg *.gls *.glo *.xdy *.nav *.out *.snm *.vrb *.mp *.synctex.gz

realclean: clean
	\rm -f *.pdf

final:
	if [ -f *.aux ]; then make clean; fi
	make document
	make clean
