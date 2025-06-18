FINAL_DIR=final

LATEXMK=latexmk -pdf -silent -file-line-error -halt-on-error -outdir=$(FINAL_DIR) 

range-for-ext.pdf:	*.tex config/*.tex
	$(LATEXMK) -jobname=range-for-ext slides
