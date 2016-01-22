# CS 383 HW #1 - Makefile

FILES = hw1.tex
CC = latex
FLAGS = -output-format=pdf

all: hw1.pdf

hw1.pdf: hw1.tex
		${CC} ${FLAGS} ${FILES}

clean:
	rm -f hw1.aux hw1.dvi hw1.log hw1.pdf