# Snake Game

This is a simple copy of the famous Snake Game using Java and the Swing library for the graphical user interface.

## How to Run

1. Ensure you have Java installed on your system.
2. Compile Java files:
    ```bash
    javac GameFrame.java GamePanel.java SnakeGame.java
    ```
3. Run:
    ```bash
    java SnakeGame
    ```

## Project Structure

The project consists of the following files:

- **GameFrame.java**: This file sets up the main game window using `JFrame`. It adds the game panel where the actual game takes place.
  
- **GamePanel.java**: This file handles the core game logic, including drawing the snake, moving it, generating apples, detecting collisions, and displaying the score. It implements the `ActionListener` interface to handle game updates and the `KeyAdapter` class to handle user input for controlling the snake.

- **SnakeGame.java**: This file contains the `main` method which starts the game by creating a new instance of `GameFrame`.

## Game Controls

- **Arrow keys**: Use the arrow keys on your keyboard to control the direction of the snake (up, down, left, right).
  
## Objective

The objective of the game is to eat the red apples that appear on the screen. Each apple eaten will increase the size of the snake and your score. The game ends if the snake runs into the walls or itself.

## Features

- Smooth snake movement using a timer.
- Randomly generated apples.
- Score display in the game.
- Simple "Game Over" screen when the game ends.

## License

This project is open-source and can be freely used or modified.

