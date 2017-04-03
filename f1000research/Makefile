
%.pdf: %.md
	pandoc -o $@ --template f1000.template -t latex --smart --filter pandoc-citeproc $<
