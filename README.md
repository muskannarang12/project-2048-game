This Java program is an enhanced version of the popular 2048 game. The main features of this implementation include an increased board size, a higher winning tile value, and an improved user interface for better gameplay experience.

Key Features:
Board Size: The game board has been expanded to 8x8, allowing for a more challenging and engaging experience.
Winning Tile: The target tile to win the game has been set to 4096, raising the difficulty and making the game more interesting.
User Interface: The user interface has been enhanced for clarity and ease of use, with clear instructions and a well-formatted display of the game board.
How It Works:
The game starts with an empty 8x8 board and two initial tiles, either 2 or 4.
Players can move the tiles using the 'W', 'A', 'S', and 'D' keys to shift tiles up, left, down, and right, respectively.
When two tiles with the same number collide, they merge into a single tile with their combined value.
After each move, a new tile (2 or 4) is added to the board at a random empty position.
The game continues until there are no possible moves left.
The player wins the game by creating a tile with the value of 4096.
Core Methods:
addNewTile(): Adds a new tile (2 or 4) at a random empty position on the board.
printBoard(): Displays the current state of the board in a clear and formatted manner.
canMove(): Checks if any moves are possible, either by finding an empty spot or adjacent tiles with the same value.
Movement Methods (moveLeft(), moveRight(), moveUp(), moveDown()): Handle tile movement and merging for the respective directions.
rotateBoard(): Rotates the board 90 degrees clockwise, used to simplify the implementation of movement in all directions.
hasWon(): Checks if the player has reached the winning tile (4096).
play(): The main game loop, handling user input, updating the board, and checking game status.
