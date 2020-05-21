# 2048

## Goal: 
Create an adversarial search agent to play the 2048-puzzle game.

2048 is played on a 4x4 grid with numbered tiles which can slide up, down, left, or right. This game can be modeled as a two player game, in which the computer AI generates a 2- or 4-tile placed randomly on the board, and the player then selects a direction to move the tiles. Note that the tiles move until they either (1) collide with another tile, or (2) collide with the edge of the grid. If two tiles of the same number collide in a move, they merge into a single tile valued at the sum of the two originals. The resulting tile cannot merge with another tile again in the same move.

## Skeleton Code
• Read-only: GameManager.py. This is the driver program that loads your Computer AI and Player AI and begins a game where they compete with each other.
• Read-only: Grid.py This module defines the Grid object, along with some useful operations: move(), getAvailableCells(), insertTile(), and clone(), which you may use in your code.
• Read-only: BaseAI.py This is the base class for any AI component. All AIs inherit from this module, and implement the getMove() function, which takes a Grid object as parameter and returns a move (there are different ”moves” for different AIs).
• Read-only: ComputerAI.py. This inherits from BaseAI. The getMove() function returns a computer action that is a tuple (x, y) indicating the place you want to place a tile.
• **Writable**: IntelligentAgent.py. File that needs to be created. The IntelligentAgent class should inherit from BaseAI. The getMove() function to implement must return a number that indicates the player’s action. In particular, 0 stands for ”Up”, 1 stands for ”Down”, 2 stands for ”Left”, and 3 stands for ”Right”. This is where the player-optimizing logic lives and is executed.
• Read-only: BaseDisplayer.py and Displayer.py. These print the grid.

## To Execute:
    $ python3 GameManager.py
    
## Notes:
Player AI is allowed 0.2 seconds to come up with each move.

## Implementation details:
1. Expectiminimax Algorithm
2. Alpha-beta pruning
3. Heuristic function with heuristic weights



