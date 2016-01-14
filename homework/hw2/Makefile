CC=gcc
CFLAGS=-ggdb

all: client server

client: client.c DieWithMessage.c
	$(CC) $(CFLAGS) -o client client.c DieWithMessage.c

server: server.c DieWithMessage.c TCPServerUtility.c AddressUtility.c
	$(CC) $(CFLAGS) -o server server.c DieWithMessage.c TCPServerUtility.c AddressUtility.c

clean:
	rm -rf client server client.dSYM server.dSYM