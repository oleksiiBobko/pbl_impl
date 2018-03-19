all: lsh

lsh: main.o
	g++ -o lsh main.o

main.o: src/main.c
	g++ -c src/main.c

clean veryclean:
	$(RM) lsh
