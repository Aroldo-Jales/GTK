CC = "g++"
PROJECT =  C++
SRC = main.cpp

LIBS = `pkg-config opencv4 gtkmm-3.0 --cflags --libs` 

$(PROJECT) : $(SRC)
	$(CC) $(SRC) -o $(PROJECT) $(LIBS)
