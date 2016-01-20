LATEXMK=../latexmk/latexmk

all: note

note: note.tex
	$(LATEXMK) -pdf note.tex -halt-on-error

wygant: wygant_summary.tex
	$(LATEXMK) -pdf wygant_summary.tex -halt-on-error

clean:
	$(LATEXMK) -C note.tex wygant_summary.tex
	rm *~
