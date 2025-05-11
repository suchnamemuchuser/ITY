PROJ=proj5

$(PROJ).pdf: $(PROJ).tex
	pdflatex $(PROJ).tex
	pdflatex $(PROJ).tex

clean:
	rm -f $(PROJ).aux $(PROJ).log $(PROJ).out $(PROJ).toc $(PROJ).nav $(PROJ).snm

clean-all: clean
	rm -f $(PROJ).pdf
