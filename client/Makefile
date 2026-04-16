CXX = g++
CXXFLAGS = -Wall -Iinclude
SRC = src/main.cpp
OUT = bin/main.exe

run: build
	./$(OUT)

build:
	$(CXX) $(CXXFLAGS) $(SRC) -o $(OUT)

clean:
	rm -f $(OUT)