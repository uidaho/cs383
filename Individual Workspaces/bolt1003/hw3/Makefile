# CS 383 HW #2 - Makefile

LFILE    = bolt1003
LATEX    = latex
LFLAGS   = -output-format=pdf
PLANTUML = java -jar diagrams/plantuml.jar
PFLAGS   = -tpng
PFILES   = diagrams/

all: ${LFILE}.pdf

${LFILE}.pdf: 
	${PLANTUML} ${PFLAGS} ${PFILES}*.uml


clean:
	rm -f ${LFILE}.aux ${LFILE}.dvi ${LFILE}.toc ${LFILE}.log ${LFILE}.pdf ${PFILES}*.png
	
	
	
	
	
	
	
	
	
