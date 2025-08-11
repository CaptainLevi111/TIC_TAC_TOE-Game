# TIC_TAC_TOE-Game
Game Overview
A Windows-compatible implementation of the classic Tic-Tac-Toe game with two difficulty levels and score tracking.

Features
Two difficulty modes:

Human (Standard): Computer makes basic moves

God (Impossible): Computer plays optimally and cannot be beaten

Score tracking (Wins/Losses/Draws)

Clear console display

Random first player selection

Input validation

Requirements
Windows OS

C compiler (MSVC, MinGW, or compatible)

How to Run
Compile the program:

text
gcc tictactoe.c -o tictactoe.exe
Run the executable:

text
tictactoe.exe
Gameplay Instructions
Select difficulty level when prompted

Players take turns entering moves:

Player uses X

Computer uses O

Enter moves as row and column numbers (1-3)

Example: "1 2" for first row, second column

Game continues until someone wins or it's a draw

Choose to play again or exit when game ends

Winning Conditions
Get three of your marks in a row (horizontal, vertical, or diagonal)

If all squares are filled with no winner, it's a draw

Tips
In God mode, the best you can do is force a draw!

Try to control the center square when possible

Watch for opportunities to create two winning paths simultaneously

Enjoy the game! 🎉
