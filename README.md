1. Project Title

Snake and Ladders Game in C

A simple terminal-based Snake and Ladders game built using the C programming language.
This project is ideal for beginners and academic submissions.
Conditional statements

2. Objective

The main objective of this project is to implement a basic Snake and Ladders game using C programming concepts such as:

Loops

Conditional statements

Functions

Random number generation

Simple game logic (snakes, ladders, and movement rules)

The game allows a single player to roll a dice and move from position 0 to 100, interacting with snakes and ladders on the board.
3. How to Compile and Run the Program
gcc snake-and-ladders

4. Sample Output

5. Important Notes / Assumptions

Dice numbers range from 1 to 6.

Landing on a snake head moves the player down to a lower position.

Landing on a ladder start moves the player higher.

The player must reach exactly 100 to win.

If the dice value exceeds 100, the player stays in the same place.

Works on all major C compilers (GCC, MinGW, Turbo C).

The program uses rand() for dice generation.
