# CS 383 HW #2 - PlantUML Makefile

FILE = hw2-uml-team4
CC = java -jar plantuml.jar
FLAGS = -tlatex

all: ${FILE}.tex

${FILE}.tex: ${FILE}.uml
	${CC} ${FLAGS} ${FILE}.uml

clean:
	rm -f ${FILE}.latex