all: clean doc display

clean:
	$(RM) CBSM-IoT.aux CBSM-IoT.log CBSM-IoT.out CBSM-IoT.pdf

doc:
	pdflatex CBSM-IoT.tex; \
	bibtex CBSM-IoT; \
	pdflatex CBSM-IoT.tex; \
	pdflatex CBSM-IoT.tex; \

display:
	zathura CBSM-IoT.pdf
