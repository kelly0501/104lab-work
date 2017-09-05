all: bin/lab3

bin/lab3: bin/attackMove.o bin/battle.o bin/pokemon.o
	g++ -g -Wall bin/attackMove.o bin/battle.o bin/pokemon.o main.cpp -o bin/lab3

bin/attackMove.o: lib/attackMove.h src/attackMove.cpp
	g++ -g -Wall -c src/attackMove.cpp -o bin/attackMove.o

bin/battle.o: lib/battle.h src/battle.cpp
	g++ -g -Wall -c src/battle.cpp -o bin/battle.o

bin/pokemon.o: lib/pokemon.h src/pokemon.cpp
	g++ -g -Wall -c src/pokemon.cpp -o pokemon.o	