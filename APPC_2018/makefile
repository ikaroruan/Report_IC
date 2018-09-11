report.pdf: report.tex references.bib
	pdflatex report
	bibtex report
	pdflatex report
	pdflatex report

clean:
	@rm report.aux
	@rm report.log
	@echo Clean done!
