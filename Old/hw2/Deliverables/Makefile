# CS 383 HW #2 - Makefile

LFILE    = hw2-team4
LATEX    = latex
LFLAGS   = -output-format=pdf
PLANTUML = java -jar diagrams/plantuml.jar
PFLAGS   = -tpng
PFILES   = diagrams/

all: ${LFILE}.pdf

${LFILE}.pdf: ${LFILE}.tex diagrams
	${PLANTUML} ${PFLAGS} ${PFILES}*.uml
	${LATEX} ${LFLAGS} ${LFILE}.tex
	${LATEX} ${LFLAGS} ${LFILE}.tex

clean:
	rm -f ${LFILE}.aux ${LFILE}.dvi ${LFILE}.toc ${LFILE}.log ${LFILE}.pdf ${PFILES}*.png
