TARGET := notes

all: $(TARGET).pdf

$(TARGET).pdf: *.tex *.bib
	pdflatex $(TARGET)
	bibtex   $(TARGET)
	pdflatex $(TARGET)
	pdflatex $(TARGET)

clean:
	rm -f *.bbl *.blg *.aux *.log
	rm -f *Notes.bib *.pdf
