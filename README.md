Snake Game README
Overview
This is a simple implementation of the classic Snake game using Python's Tkinter library. The player controls the snake to collect food while avoiding collisions with itself and the walls.

Features
-Basic Gameplay: Move the snake in four directions to collect food.
-Scoring: The score increases with each piece of food collected.
-Game Over Conditions: The game ends when the snake collides with itself or the window boundaries.

Controls
Use the arrow keys to move the snake:
-Up Arrow: Move up
-Down Arrow: Move down
-Left Arrow: Move left
-Right Arrow: Move right
 
Game Rules
-The snake grows longer each time it eats food.
-The game ends if the snake collides with the walls of the window or with itself.
-The current score is displayed at the top left of the window.
-A "Game Over" message is displayed at the center when the game ends.

Code Explanation
-Tile Class: Represents each segment of the snake and the food.
-Game Loop: The draw() function is called repeatedly to update the game state.
-Movement Logic: The snake's position is updated based on the current direction.
-Collision Detection: The game checks for wall collisions and self-collisions.

Customization
Feel free to modify the following parameters in the code:
ROWS and COLS: Change the grid size.
TILE_SIZE: Adjust the size of each tile.
Colors: Modify the fill colors for the snake and food in the draw() function.

Acknowledgments
Thanks to the Python community for creating the Tkinter library, which makes GUI programming simple and fun.
