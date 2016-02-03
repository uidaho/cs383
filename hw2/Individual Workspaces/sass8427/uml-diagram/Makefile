# CS 383 HW #2 - PlantUML Makefile

FILE = Project_Mgmt
CC = java -jar plantuml.jar
FLAGS = -tlatex

all: ${FILE}.tex

${FILE}.tex: ${FILE}.uml
	${CC} ${FLAGS} ${FILE}.uml

clean:
	rm -f ${FILE}.latex