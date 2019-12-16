# Assignment 4
## 1. The Othello game
___
Othello (Reversi) is known as a strategy board game for two players on an 8×8 board. There are totally sixty-four identical game pieces called disks. Each disk has a white side and a black side. Othello is played by turns by placing disks on the board with their assigned color facing up. During a play, any disks of the opponent's color that are in a straight line (horizontal, vertical, and diagonal) and bounded by the disk just placed and another disk of the current player's color are turned over to the current player's color. The objective of the game is to have the majority of disks turned to display your color when the last playable empty square is filled. The following is a nice introduction on how to play Othello. http://radagast.se/othello/Help/strategy.html
___
Your task is to write an AI program to play Othello with a human player. Your tasks include
1.	Implement an Othello playing interface that one can play the game.
2.	Design a heuristic function for the intermediate states.
___
## Hints: 
The design of the heuristic functions.
1.	##### Intuitive design
    - The state with more pieces in your color is more favoriable.

2.	##### Frontier disks
    - Frontier disks are the pieces that are adjacent to open spaces. These disks are often volatile because they are easily flipped back and forth between the two players. Therefore, it is intuitive that we try to minimize these pieces for ourselves and maximizing them for the other player so that we have a solid base of pieces.

3.	##### Positions
     - Disks on the side are more valuable than the inner ones. Disks at the corner are more valuable than the others.