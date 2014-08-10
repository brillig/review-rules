
OUT = guide.pdf guide.info

all: $(OUT)

%.pdf: %.texi
	texi2pdf $<

%.info: %.texi
	makeinfo $<
