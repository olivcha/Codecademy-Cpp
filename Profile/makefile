profile: profile.o app.o
	g++ -g profile.o app.o -o profile

profile.o: profile.cpp profile.hpp
	g++ -Wall -g -c profile.cpp

app.o: app.cpp profile.hpp
	g++ -Wall -g -c app.cpp

clean:
	rm -f *.o profile