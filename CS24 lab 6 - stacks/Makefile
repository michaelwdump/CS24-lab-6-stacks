CPP = g++

usestack: usestack.o 
	$(CPP) $^ -o $@

usestack.o: usestack.cpp intstack.h
	$(CPP) -c $^