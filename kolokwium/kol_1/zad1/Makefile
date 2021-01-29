all: main.o address.o employee.o
	g++ -g main.o address.o employee.o -o myProgram

main.o: main.cpp
	g++ -c -Wall main.cpp

address.o: address.cpp
	g++ -c -Wall address.cpp

employee.o: employee.cpp
	g++ -c -Wall employee.cpp
clean:
	rm -f main.o address.o employee.o myProgram
