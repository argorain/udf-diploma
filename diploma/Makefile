TEX = pdflatex

SRC = sablona-prace.tex

all: build purge

build:
	$(TEX) $(SRC)
	$(TEX) $(SRC)
	$(TEX) $(SRC)


purge:
	rm -fv *.toc *.tof *.toa *.lol *.lof *.loa *.lot *.aux *.log *.out *~ text/*.aux text/*~

clean: purge
	rm -fv *.pdf
