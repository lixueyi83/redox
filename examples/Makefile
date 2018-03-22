## To build other *.cpp file, for example example.cpp, do the following 
## $ make exe=example 


EXE=main

CPPFLAGS = -std=c++11 -lev -lhiredis -lredox_static -lpthread 

all:
	g++ ${EXE}.cpp -o ${EXE} ${CPPFLAGS}


clean:
	
