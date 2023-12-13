# Winter-Internship

Leap Frog Jump Game in Python
Overview :
Welcome to the Leap Frog Jump Game project in Python! This implementation replicates the classic 'Frog Leap' puzzle game where frogs must strategically jump over one another to switch positions.

Problem Statement :
The task is to create a console-based Frog Leap Game. The game follows these rules:

The left set of frogs can only move right, and the right set of frogs can only move left.
Frogs can move forward one space or jump two spaces by leaping over another frog from the opposite side.
The puzzle is considered solved when the two sets of frogs have switched positions.
How to Play
Initial Display:


[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', 'G', 'G', '_', 'B', 'B', 'B']
Here, 'G' represents Green frogs on the left side, 'B' represents brown frogs on the right side, and '_' defines the position of an empty leaf.

Accept Input:

Enter the position of the frog you want to move. For example, if you enter position 2, the game will look like this:


[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', 'G', '_', 'G', 'B', 'B', 'B']
Invalid Moves:

Entered position should be between 0 to 6 or the character 'q' to quit the game.
The selected position cannot be the position of an empty leaf.
If the selected frog's position cannot perform the constraints given, the move is invalid.
Making a Move:

The program will prompt you to enter the position of the frog you want to move.
If the input is 'q', the game ends, and you lose.
If the input is a valid integer, the program will check if the move is valid according to the game rules and make the appropriate move.
Winning Condition:

The puzzle is considered solved when the two sets of frogs have switched positions. If the arrangement is:


['B', 'B', 'B', '_', 'G', 'G', 'G']
