CFLAGS = -std=c++17 -O2
LDFLAGS = -lglfw -lvulkan -ldl -lpthread -lX11 -lXxf86vm -lXrandr -lXi -lGL

Catur: main.cpp
		g++ $(CFLAGS) -o Catur main.cpp $(LDFLAGS)

.PHONY: test clean

test: Catur
	./Catur


clean:
	rm -f Catur
