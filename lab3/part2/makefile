BIN_DIR = exe

all: $(BIN_DIR)/lab3

$(BIN_DIR)/lab3: $(BIN_DIR)/attackMove.o $(BIN_DIR)/battle.o $(BIN_DIR)/pokemon.o
	g++ -g -Wall $(BIN_DIR)/attackMove.o $(BIN_DIR)/battle.o $(BIN_DIR)/pokemon.o main.cpp -o bin/lab3

$(BIN_DIR)/attackMove.o: lib/attackMove.h src/attackMove.cpp
	g++ -g -Wall -c src/attackMove.cpp -o $(BIN_DIR)/attackMove.o

$(BIN_DIR)/battle.o: lib/battle.h src/battle.cpp
	g++ -g -Wall -c src/battle.cpp -o $(BIN_DIR)/battle.o

$(BIN_DIR)/pokemon.o: lib/pokemon.h src/pokemon.cpp
	g++ -g -Wall -c src/pokemon.cpp -o $(BIN_DIR)/pokemon.o	