main = DL1_AC1
resources = $(main).tex makefile

article.pdf: $(resources)
	latexmk -pdf -pdflatex='pdflatex -interaction=nonstopmode -synctex=-1' $(main).tex

clean:
	latexmk -C
