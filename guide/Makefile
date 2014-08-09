
OUT = guide.pdf

all: $(OUT)

%.pdf: %.texi
	texi2pdf $<

%.info: %.texi
	makeinfo $<
