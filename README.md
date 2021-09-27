# SnakeGame
A Small Snake game for fun.
This game is implemented using Turbo C. The game consists of many functions which perform different tasks according to the need of the game. Some of the functions used in the program are: 
1.Void setup()
2.Void draw()
3.Void input()
4.Void MakeLogic()

The game uses two main in-built functions which are kbhit() and rand().The kbhit() is basically used to see which key is pressed from the keyboard and it lets you to perform tasks accordingly.
Also, the rand() is used to generate snake food randomly. To make snake’s body we have used the concept of array. To move the snake in given direction we have made the use of switch case. Instead, we can also use the concept of enumeration which would also perform same task as switch case performs. Using for loop in the void draw() we are able to draw the wall of the snake game. Also, a major issue faced was snake’s speed. So, to decrease snake’s speed we have used 2 for loop in the main function where all the functions are called one after the other.

The symbol “#” is used for making walls of the snake. The letter “F” is used to generate food at random location. The letter “O” is used for the snake’s head and “o” is used to generate snake’s body. The score gets increased by 10 points whenever snake eats the food. Also, we can continue the game by pressing ‘Y’ or ‘y’.

The game gets over if the snake hits the wall or else it hits itself.

