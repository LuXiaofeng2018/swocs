all: retraso bateria

bateria: bateria.c gen_bateria.pl makefile
	gcc bateria.c -lm -Os -Wall -o bateria
	rm i-* o-* f-* a-*
	./bateria

retraso: retraso.c makefile
	gcc retraso.c -Os -Wall -o retraso
	rm r-*

clean:
	rm i-* o-* f-* a-* r-* script-* bateria retraso
