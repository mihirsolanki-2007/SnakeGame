Setting up the game screen: The game will be displayed in a window with a fixed width and height. The game screen will be drawn using the pygame.display.set_mode() method.

Game Entities:

Snake: The snake is a list of squares. Each square is represented as a block of pixels.
Food: The food is a single square that the snake eats to grow in length.
Walls: The game has boundaries (the walls). If the snake touches them, the game ends.
Score: The score increases when the snake eats food.
Game Loop: The main part of the game is a loop that:

Updates the snake's position based on user input (using arrow keys).
Checks for collisions with food, walls, or the snake's own body.
Redraws the screen.
Updates the score.
