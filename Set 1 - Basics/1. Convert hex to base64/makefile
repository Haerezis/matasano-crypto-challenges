CC=gcc
CFLAGS=-Wall
LDLIB=

all:code

code:code.o
	$(CC) $(CFLAGS) -o $@ $^ $(LDLIB)

code.o:code.c code.h
	$(CC) $(CFLAGS) -c -o $@ $<

clean:
	rm *.o code
