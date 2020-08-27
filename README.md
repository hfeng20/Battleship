# Battleship
Play against the computer in a Java-based Battleship game.

Directions:
  Place five ships of lengths 2,3,3,4, and 5 among a 10x10 board, and the compuer will randomly do the same on a different board.
  You and the computer will then take turns guessing locations on the 10x10 board and try to hit the ships on eachothers' boards.
  The computer will randomly generate guessing locations. Your objective is to hit and sink all ship locations
  on the computer's grid before the computer sinks yours. Good Luck!

Note:
  When placing ships, you are asked to indicate one "starting point" (x,y) on the grid and a direction for the ship. 
  If the direction is vertical, the starting point is the first index of that ship, and subsequent indices will be placed moving downward.
  If the direction is horizontal, the starting point is the first index of that ship, and subsequent indices will be placed moving to the right.
  Example:
    Ship length: 3
    Starting point: (9,9) 
    Direction: vertical
    The starting point is within the limits of the board but as the ship is placed on the grid moving downward, there is not enough space 
    to fully place the ship.
