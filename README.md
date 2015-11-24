c-projects
==========

Here lie some side projects I've been working on.
If you can make use of them, feel free to use them without giving me any credit.
Currently, there are two tile-based games - Conway's Game of Life, and Snake.
Both were implemented as a way to learn c.

note: Both games require SDL2 to run. Install it from your favorite package
manager.

----
#Installation
Warning, both of these games expect sdlgrid.{c,h} to be in the parent directory.
If you move around the directory tree, then it's on you to change the makefile.

##To play Snake
    cd Snake
    make
    ./bin/snake.o

##To "play" Conway's Game of Life
    cd ConwayGOL
    make
    ./bin/conwaygol.o
