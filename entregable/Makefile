
all: compile

compile: 
	latexmk -g -pdf cluster_design.tex

clean:
	latexmk -c

clean_all: clean
	latexmk -C

run: *.pdf
	xdg-open *.pdf &> /dev/null &
