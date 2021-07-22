main:./src/main.cpp ./build/libdynamic.so
	g++ ./src/main.cpp -I./include/ -L./build/ -ldynamic -o./build/main
./build/libdynamic.so:
	g++ ./src/a.cpp ./src/b.cpp ./src/c.cpp -I./include/ -fPIC -shared -o./build/libdynamic.so

