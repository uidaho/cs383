# CS 383 HW #2 - Makefile

LFILE = hw2-team4
LATEX = latex
LFLAGS = -output-format=pdf
PLANTUML = java -jar diagrams/plantuml.jar
PFLAGS = -tpng
PFILES = diagrams/jank6275.uml #diagrams/bolt1003.uml diagrams/wern0096.uml diagrams/sass8427.uml diagrams/dani2918.uml diagrams/boss2849.uml diagrams/snev7821.uml diagrams/alsh5301.uml
PNGS = diagrams/jank6275.png #diagrams/bolt1003.png diagrams/wern0096.png diagrams/sass8427.png diagrams/dani2918.png diagrams/boss2849.png diagrams/snev7821.png diagrams/alsh5301.png

all: ${LFILE}.pdf

${LFILE}.pdf: ${LFILE}.tex ${PNGS}
	${LATEX} ${LFLAGS} ${LFILE}.tex
	${LATEX} ${LFLAGS} ${LFILE}.tex

${PNGS}: ${PFILES}
	${PLANTUML} ${PFLAGS} ${PFILES}
	
clean:
	rm -f ${LFILE}.aux ${LFILE}.dvi ${LFILE}.toc ${LFILE}.log ${LFILE}.pdf ${PNGS}
	
	
	
	
	
	
	
	
	
