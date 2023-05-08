all:
	make clean
	make default

clean:
	rm -rf ./writer ./*.o

objects: writer.c
	$(CC) -g -Wall -c -o writer.o writer.c

default: writer.o objects
	$(CC) -g -Wall -o writer writer.o
