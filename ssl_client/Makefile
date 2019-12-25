all: ssl_client

ssl_client: main.o 
	g++ -g -w -o ssl_client main.o -lssl -lcrypto -lpthread

main.o:
	g++ -g -w -c -o main.o main.cpp

clean:
	rm -f ssl_client
	rm -f *.o
