# Game with MiniMax (Alpha Beta pruning) algorithm
Available here - https://ilyashenkoa.github.io/minimax-typescript-material/


## This is a remix of another MiniMax game, developed on C# - https://github.com/IlyashenkoA/minimax-game
## Project based on React, Redux, TypeScript, and Material UI

### Rules:
* At the start of the game, a random string of numbers is generated, consisting of 0 and 1, for example, "101011"
* Players perform moves in turn. The move involves replacing any two adjacent numbers, based on the following conditions: the pair of numbers 00 gives 1, 01 -> 0, 10 -> 1, and 11 -> 0. Only one pair of numbers can be substituted per turn. 
* The game ends when 2 numbers are obtained. If both numbers are the same (11 or 00), then the player wins who started the game is. If they are different (10 or 01), then the second player wins.

## Features
* Possibility to choose the length of the row (optimal and maximum length - 10)
* Ability to choose, who starts the game first
* If the game was not finished and the page was reloaded, the data will be saved
