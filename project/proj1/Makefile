CC=gcc
CFLAGS=-ggdb

all: http-client

http-client: http-client.c DieWithMessage.c
	$(CC) $(CFLAGS) -o http-client http-client.c DieWithMessage.c

server: DieWithMessage.c TCPServerUtility.c AddressUtility.c
	$(CC) $(CFLAGS) -o DieWithMessage.c TCPServerUtility.c AddressUtility.c

clean:
	rm -rf client client.dSYM server.dSYM
