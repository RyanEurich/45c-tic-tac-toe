# 45c-tic-tac-toe
Lab 2: Command-line Tic Tac Toe
Purpose of this Lab:

The purpose of this lab is to get you used to arrays in C++ and also have some fun with the terminal. If you have not completed Lab 1 by now, please do so. You will need to get your development environment up and running.

Introduction to the Lab :

In this lab, we will be creating a command-line Tic Tac Toe game. For those not familiar with Tic Tac Toe, refer to this Wikipedia page (Links to an external site)Links to an external site. for it. In short, Tic Tac Toe is a 2-player game where one player's game piece is X and the second player's game piece is O (letter). The players take turns putting 1 of their game pieces in 1 of the empty slots in the 3 by 3 board. The first player to get 3 of their game pieces to align (vertically, horizontally or diagonally) wins. If the board has no empty slots and neither of the players has already won, no one wins and the game ends in a tie.

Program instructions:

Starter Code Download LinkDownload Starter Code Download Link

Complete the functions defined in Functions.h to code the game

Functions.h:

Can only be updated to add includes if needed otherwise no new functions are needed
Functions.cpp :

void runGame()
Handles the main game logic
Prompts the user by printing to the console when needed
Calls other functions as needed to run the game
void initBoard(board)
Initializes the given board to empty pieces
void placeAPiece(x, y, piece, board)
Places the passed-in piece to the given coordinate
bool checkForWinner(piece, board)
Checks to see if the passed-in player (piece) won the game or not, and returns the result
bool checkForDraw(board)
Checks to see if the game has come to a draw, and returns the result
void displayBoard(board)
Prints the board to the console in the correct format
lab2.cpp :

Call your main game function from Functions.cpp
Important details:

X will always start the game no matter which piece was placed in the last move of the previous game
Use “X” and “O” (capital letters) for the placed pieces and “-” (hyphen) empty pieces
Use “|” (vertical bar) and “-” (hyphen) to draw the board 
Don’t add any extra spaces and always finish printing strings with an endl
The input prompt should be “Enter coordinate for {}. Input should be X Y”
Game ending should either be “{} Won” or “Draw”
The prompt after the game is finished should be “Do you want to play again?”
“Y” or “y” should restart the game
“N” or “n” should exit the game
Print “Done” after the user is done playing
For your coordinates, follow the convention used in the sample output of the lab description, where the x coordinate specifies the row and the y coordinate specifies the column.
Here is an example of a game being played:

Tic Tac Toe Example
