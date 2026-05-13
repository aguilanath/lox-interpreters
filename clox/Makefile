CC = gcc
CCFLAGS = -g -std=c11
WARNFLAGS = -Wall -Wextra -pedantic

main: main.c
	$(CC) $(CCFLAGS) $(WARNFLAGS) main.c -o main

.PHONY: clean
clean:
	rm -f main
