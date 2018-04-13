INCLUDE = $(shell pkg-config --cflags opencv)
LIBS    = $(shell pkg-config --libs   opencv)

all:*.cpp 
	nvcc  -ccbin g++  -I $(INCLUDE) *.cpp -o  ../tracking  $(LIBS) -lpthread 
clean:
	rm tracking
