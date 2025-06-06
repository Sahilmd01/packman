# Pacman Game

A simple Pacman game implementation using JavaScript and HTML5 Canvas.

## Features

- Smooth movement with directional controls.
- Collision detection with walls and ghosts.
- Eating mechanic that increases the score.
- Animated Pacman sprite with mouth opening/closing.
- Rotates sprite based on movement direction.

## How It Works

- The game map is represented as a 2D array (`map`), where:
  - `1` = Wall
  - `2` = Food pellet
  - `3` = Empty space after eating pellet
- Pacman moves in the current direction unless blocked by a wall.
- Pacman can change direction if the new direction is not blocked.
- When Pacman moves over a pellet, it is eaten and the score increases.
- Collision with ghosts triggers game over.

## Setup and Usage

1. Clone or download the repository.
2. Open the `index.html` file in a modern web browser.
3. Use arrow keys (or configured controls) to move Pacman around the maze.

## Code Highlights

- `Pacman` class manages player movement, animation, collision, and eating logic.
- Uses sprite sheet animation cycling every 100ms.
- Collision detection based on Pacman’s position relative to the map grid.
- Direction constants ensure clean and understandable movement logic.

## Dependencies

- None (Vanilla JavaScript and HTML5 Canvas)

## License

This project is open source and available under the MIT License.

---



