all: clean loli.pdf

loli.pdf: loli.dvi
	dvipdf loli.dvi
loli.dvi:
	latex ../motor/loli.tex

clean:
	rm loli.* -f
