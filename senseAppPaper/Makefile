
all: paper


paper: IoTSecurityIntegrationPaper.tex
	pdflatex -output-directory ./tmp IoTSecurityIntegrationPaper.tex
	bibtex ./tmp/IoTSecurityIntegrationPaper
	pdflatex -output-directory ./tmp IoTSecurityIntegrationPaper.tex
	pdflatex -output-directory ./tmp IoTSecurityIntegrationPaper.tex
	mv tmp/IoTSecurityIntegrationPaper.pdf .