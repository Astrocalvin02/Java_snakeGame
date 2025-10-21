# Java Snake Game

A classic Snake game implemented in Java using Swing for the graphical user interface. The player controls a snake that grows by eating apples while avoiding collisions with walls or itself.

This project is based on the tutorial from [ZetCode](https://zetcode.com/javagames/snake/).

## Features

- Simple and intuitive controls using arrow keys
- Snake grows when eating apples
- Game over on collision with walls or self
- Visual representation using images for snake head, body, and apple

## Prerequisites

- Java Development Kit (JDK) 8 or higher installed on your system

## How to Run

1. Ensure you have Java installed. You can check by running `java -version` in your terminal.

2. Navigate to the project directory:
   ```
   cd c:/Users/cals_astro/Documents/Java_Snake_Game
   
   ```

3. Compile the Java files:
   ```
   javac src/com/zetcode/*.java
   ```

4. Run the game:
   ```
   java -cp src com.zetcode.Snake
   ```

The game window will open, and you can start playing using the arrow keys.

## Project Structure

- `src/com/zetcode/Board.java`: Contains the game board logic, drawing, and event handling.
- `src/com/zetcode/Snake.java`: Main class that sets up the JFrame and starts the application.
- `src/resources/`: Directory containing image assets (apple.png, dot.png, head.png).
- `snake.png`: Screenshot of the game.

## Controls

- Arrow keys: Move the snake (Up, Down, Left, Right)
- Avoid hitting walls or the snake's own body
- Eat apples to grow and increase score

## License

This project is licensed under the terms specified in the LICENSE file.
