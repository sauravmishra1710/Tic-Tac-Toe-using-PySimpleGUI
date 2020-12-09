# Tic-Tac-Toe--using-PySimpleGUI

tic-tac-toe Game using PySimpleGUI

An update to the initial version where once the current board is
Won/Complete, a Yes/No popup would let the players decide
if they would want to continue playing.

YES would let them continue playing the game.
NO would take the control back to the game
initialization window to start a fresh session with
new players.

## Design pattern 

Multiple Windows Using read_all_windows() @
https://github.com/PySimpleGUI/PySimpleGUI/blob/master/DemoPrograms/Demo_Design_Pattern_Multiple_Windows1.py

Only 1 window at a time is visible/active on the screen.

## Game Workflows

1. Game launched with the INIT_WINDOW dialog to allow enter the players details and specifications.

2. INIT_WINDOW opens the GAME_BOARD screen.

2. Closing the GAME_BOARD exits the game and returns to the INIT_WINDOW.

3. Exiting the INIT_WINDOW would exit the game.

4. RESET would reset thecurrent game session and
start over a fresh board.
