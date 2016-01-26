# CS 383 HW #1 - Makefile

FILE = hw1
CC = latex
FLAGS = -output-format=pdf

all: ${FILE}.pdf

${FILE}.pdf: ${FILE}.tex
	${CC} ${FLAGS} ${FILE}.tex
	${CC} ${FLAGS} ${FILE}.tex

clean:
	rm -f ${FILE}.aux ${FILE}.dvi ${FILE}.log ${FILE}.pdf