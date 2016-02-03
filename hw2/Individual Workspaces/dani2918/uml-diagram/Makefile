# CS 383 HW #2 - PlantUML Makefile

FILE = dani2918
CC = java -jar plantuml.jar
FLAGS = -tpng

all: ${FILE}.tex

${FILE}.tex: ${FILE}.uml
	${CC} ${FLAGS} ${FILE}.uml

clean:
	rm -f ${FILE}.latex