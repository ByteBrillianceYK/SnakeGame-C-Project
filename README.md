# SnakeGame-C-Project
Learning the basics of C and leveraging the skills to build a game which i played the most at some point 


In this project, the task is to implement a basic Snake Game. Below given some functionalities of this game:

The snake is represented with a 0(zero) symbol.
The fruit is represented with an *(asterisk) symbol.
The snake can move in any direction according to the user with the help of the keyboard (W, A, S, D keys).
When the snake eats a fruit the score will increase by 10 points.
The fruit will generate automatically within the boundaries.
Whenever the snake will touch the boundary the game is over.
Steps to create this game:

There will be four user-defined functions.
Build a boundary within which the game will be played.
The fruits are generated randomly.
Then increase the score whenever the snake eats a fruit.
The user-defined functions created in this program are given below:

Draw(): This function creates the boundary in which the game will be played.
Setup(): This function will set the position of the fruit within the boundary.
Input(): This function will take the input from the keyboard.
Logic(): This function will set the movement of the snake.
Built-in functions used:

kbhit(): This function in C is used to determine if a key has been pressed or not. To use this function in a program include the header file conio.h. If a key has been pressed, then it returns a non-zero value otherwise it returns zero.
rand(): The rand() function is declared in stdlib.h. It returns a random integer value every time it is called.
