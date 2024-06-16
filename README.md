# java-project

Import Statements:

java
Copy code
import java.util.Scanner;
This line imports the Scanner class from the java.util package, allowing user input from the console.

Class Declaration:

java
Copy code
public class TicTacToe {
This line defines a public class named TicTacToe.

Class Variables:

java
Copy code
private static char[][] board = {
    {' ', ' ', ' '},
    {' ', ' ', ' '},
    {' ', ' ', ' '}
};
private static char currentPlayer = 'X';
Here, board is a 2D array representing the Tic Tac Toe game board initialized with empty spaces. currentPlayer represents the player currently making a move, initialized as 'X'.

Main Method:

java
Copy code
public static void main(String[] args) {
    // Main game logic
}
The main method is the entry point of the program where the game logic resides.

Game Loop:

java
Copy code
while (true) {
    // Game logic
}
This while loop runs indefinitely until the game is over. It iterates through each turn of the game.

Printing the Board:

java
Copy code
private static void printBoard() {
    // Printing the Tic Tac Toe board
}
The printBoard method prints the current state of the game board to the console.

Player Move:

java
Copy code
private static void playerMove(Scanner scanner) {
    // Prompting the player for their move
}
The playerMove method prompts the current player to enter their move (row and column) and updates the game board accordingly.

Switching Players:

java
Copy code
private static void switchPlayer() {
    // Switching the current player
}
The switchPlayer method switches the current player between 'X' and 'O' after each turn.

Checking if the Board is Full:

java
Copy code
private static boolean isBoardFull() {
    // Checking if the game board is full
}
The isBoardFull method checks if the game board is full (no empty spaces left).

Checking if the Game is Over:

java
Copy code
private static boolean isGameOver() {
    // Checking if the game is over
}
The isGameOver method checks if the game is over by calling helper methods to check for winning conditions (rows, columns, diagonals).

Checking Rows for a Win:

java
Copy code
private static boolean checkRows() {
    // Checking rows for a win
}
The checkRows method checks if any row contains three consecutive marks by the current player.

Checking Columns for a Win:

java
Copy code
private static boolean checkColumns() {
    // Checking columns for a win
}
The checkColumns method checks if any column contains three consecutive marks by the current player.

Checking Diagonals for a Win:

java
Copy code
private static boolean checkDiagonals() {
    // Checking diagonals for a win
}
The checkDiagonals method checks if any diagonal contains three consecutive marks by the current player.
