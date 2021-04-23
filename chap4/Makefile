# Make file for chapter 4 of The c programming language 2nd example code
CC = clang
CFLAGS = -g -Wall

atof.o: atof.c
	$(CC) $(CFLAGS) -c atof.c

atof: atof.o
	$(CC) $(CFLAGS) -o atof atof.o

grep.o: grep.c
	$(CC) $(CFLAGS) -c grep.c

grep: grep.o
	$(CC) $(CFLAGS) -o grep grep.o

clean:
	$(RM) *.o atof grep
