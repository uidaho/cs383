# CS 383 HW #2 - Makefile

LFILE    = *
LATEX    = latex
LFLAGS   = -output-format=pdf
PLANTUML = java -jar diagrams/plantuml.jar
PFLAGS   = -tpng
PFILES   = diagrams/

all: latex-make

latex-make: 
	${PLANTUML} ${PFLAGS} diagrams/*.uml
	${LATEX} ${LFLAGS} *use_case*.tex
	${LATEX} ${LFLAGS} functional.tex
	${LATEX} ${LFLAGS} nonfunctional.tex

clean:
	rm -f ${LFILE}.aux ${LFILE}.dvi ${LFILE}.toc ${LFILE}.log ${LFILE}.pdf ${PFILES}*.png
	
	
	
	
	
	
	
	
	
