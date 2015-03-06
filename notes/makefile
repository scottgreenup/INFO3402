

LATEX=pdflatex
LATEX_FLAGS=-file-line-error -halt-on-error -interaction nonstopmode

BASEFILE=main.tex
OUTDIR=bin

main: setup
	$(LATEX) $(LATEX_FLAGS) -output-directory $(OUTDIR) $(BASEFILE)

clean:
	rm -rf $(OUTDIR)/*

setup: $(OUTDIR)

$(OUTDIR):
	mkdir -p $(OUTDIR)

