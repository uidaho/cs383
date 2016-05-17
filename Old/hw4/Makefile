# CS 383 HW #5 - Makefile
# by jank6275

LFILE    = hw4-team3
LATEX    = latex
LFLAGS   = -output-format=pdf
PLANTUML = java -jar diagrams/plantuml.jar
PFLAGS   = -tpng
PFILES   = diagrams/

all: ${LFILE}.pdf

${LFILE}.pdf: ${LFILE}.tex
	${PLANTUML} ${PFLAGS} ${PFILES}*.uml
	${LATEX} ${LFLAGS} ${LFILE}.tex
	${LATEX} ${LFLAGS} ${LFILE}.tex

clean:
	rm -f ${LFILE}.aux ${LFILE}.dvi ${LFILE}.toc ${LFILE}.log ${LFILE}.pdf ${PFILES}*.png

overview:
	${PLANTUML} ${PFLAGS} ${PFILES}overview.uml