.PHONY: typeset

FILES=`cat index.txt`

typeset:
	pandoc                          \
	  --from         markdown       \
	  --to           latex          \
	  --template     template.tex   \
	  --out          report-bib.pdf \
	  --latex-engine xelatex        \
	  --bibliography biblio.bib     \
	  --csl style.csl               \
	  $(FILES)
