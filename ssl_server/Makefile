all: ssl_server

ssl_server: main.o 
	g++ -g -w -o ssl_server main.o -lssl -lcrypto -lpthread

main.o:
	g++ -g -w -c -o main.o main.cpp

clean:
	rm -f ssl_server
	rm -f *.o
