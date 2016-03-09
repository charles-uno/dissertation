LATEXMK=../../latexmk/latexmk

all: note

note: note.tex
	$(LATEXMK) -pdf note.tex -halt-on-error

clean:
	$(LATEXMK) -C note.tex note.tex
	rm *~
