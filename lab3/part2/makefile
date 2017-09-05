BIN_DIR = bin
CXX = g++
CPPFLAGS = -Wall -g

all: $(BIN_DIR)/lab3

$(BIN_DIR)/lab3: $(BIN_DIR)/attackMove.o $(BIN_DIR)/battle.o $(BIN_DIR)/pokemon.o
	$(CXX) $(CPPFLAGS) $(BIN_DIR)/attackMove.o $(BIN_DIR)/battle.o $(BIN_DIR)/pokemon.o main.cpp -o bin/lab3

$(BIN_DIR)/attackMove.o: lib/attackMove.h src/attackMove.cpp
	$(CXX) $(CPPFLAGS) -c src/attackMove.cpp -o $(BIN_DIR)/attackMove.o

$(BIN_DIR)/battle.o: lib/battle.h src/battle.cpp
	$(CXX) $(CPPFLAGS) -c src/battle.cpp -o $(BIN_DIR)/battle.o

$(BIN_DIR)/pokemon.o: lib/pokemon.h src/pokemon.cpp
	$(CXX) $(CPPFLAGS) -c src/pokemon.cpp -o $(BIN_DIR)/pokemon.o	