# Snake Game Overview

This project is a simple implementation of the classic Snake game using Java and the Swing framework. The game features a graphical interface where the player controls a snake to eat apples and grow in size. The game ends if the snake collides with itself or the screen borders.

## Code Summary

### GameFrame.java

The `GameFrame` class extends `JFrame` and serves as the main window of the game. It sets up the game window properties such as title, close operation, and visibility. It also adds the game panel where the actual game logic and rendering occur.


### SnakeGame.java

The `SnakeGame` class contains the `main` method, which is the entry point of the application. It creates an instance of `GameFrame`, thereby starting the game.

### GamePanel.java

The `GamePanel` class extends `JPanel` and implements `ActionListener`. This class contains the core game logic and rendering code. It handles game initialization, game loop, drawing the snake and apple, handling user input, and checking for collisions.

- **Constants and Variables**: Defines screen dimensions, unit size, game speed, and various game state variables.
- **Constructor**: Sets up the game panel properties, initializes the game, and starts the game loop timer.
- **Game Methods**: Includes methods for starting the game, drawing game components, spawning apples, moving the snake, checking for apple collisions, checking for snake collisions, and handling game over state.
- **ActionListener Implementation**: Updates game state on each timer tick and repaints the game panel.
- **KeyAdapter**: Handles user input to control the snake's direction.

This summary provides an overview of the main components and functionality of the Snake game. For detailed implementation, please refer to the source code files.
