# Tic Tac Toe Game

This is a code for `Tic Tac Toe` game in ```python```.<br>

Game has 2 difficulty levels.
1. Easy
2. Hard
***
To play the game, use this command in a LINUX terminal:

<br>

><p align="center">pyhton3 main.py</p>

<br>

Game will now begin.
***
### A Brief desciption of process of game:
1. First of all, user will be asked to select his symbol; either ```X``` or ```O```.
2. Then user will be asked to select difficulty level; either ```E``` (for EASY) or ```H``` (for HARD).
3. Once ready, press `Enter` to start the game.
4. First turn will be decided randomly and then moves will be alternate.
5. 3x3 game board will be displayed, each box having a unique id. As game progresses, box id's will be replaced by symbols.
6. In computer's turn, wait till computer select it's move.
7. In `EASY` level, computer's move is just a random selection from all the availbale moves while in `HARD` level, computer uses ```MINIMAX Algorithm``` to find best possible move.
8. In user's turn, enter box id for the block you want to move. If invalid id is chosen, error message will be displayed.
9. ```Victory``` / ```Loss``` / ```Draw``` message will be printed as soon as game ends.