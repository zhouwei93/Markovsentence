welcoome to view this page!
 here are some reference to run the program.
 this project is a minesweeper game.The goal is to fullfill a function which consumes three arguments width height number_of_mines and generates a Minesweeper board internally. The board is a rectangle with a cover over each square. It will display this board to the user and prompt for a coordinate where they predict that no mine exists (format: x-coord y-coord 0-indexed). If they struck a mine then they lose .
 first, create a 99 field indicating the game field. Secondly, set all the field with -1 indicating field that had not been clicked. Then generates random number and set mines where number is 9. Then calaulate number of mine around a coordinate being clicked and print. It calculates the number of mines and when the user click all the coordinate without mine, the user wins. If user click a blank field

To get you started with C/C++,use the following sentence to complier:


Have a look at the files, and use the terminal to build them:

    g++ -o sweep minesweeper.cpp' and then './sweep
 
