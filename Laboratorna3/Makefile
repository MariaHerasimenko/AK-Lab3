all: laboratorna3

laboratorna3: calculator.o calculator2.o
		 g++ calculator.o calculator2.o -o laboratorna3
		 
calculator.o: calculator.cpp
	 g++ -c calculator.cpp
	 
calculator2.o: calculator2.cpp
	 g++ -c calculator2.cpp
	 
clean:
	rm -rf *0 laboratorna3
