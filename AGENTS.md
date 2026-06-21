# Project: Python Snake Game

This is a classic Snake game implemented in Python using the built-in `turtle` library. It's a single-file application designed for simplicity and ease of use.

## Project Overview

- **Core Technology:** Python 3.x, `turtle` library (standard library).
- **Architecture:** Procedural game loop in a single file (`snake.py`).
- **Input Handling:** Keyboard events for both Arrow keys and WASD.
- **Visuals:** Basic geometric shapes (squares for snake/segments, circles for food).

## Getting Started

### Prerequisites
- Python 3.x installed on your system.
- No external dependencies are required.

### Running the Game
To start the game, execute the following command in the terminal:
```powershell
python snake.py
```

## Development Conventions

- **Single File:** The entire game logic, including UI setup, input handling, and game loop, resides in `snake.py`.
- **State Management:** Global variables are used for `score`, `high_score`, and `delay`.
- **Game Logic:**
    - Collision detection is distance-based (`head.distance(target) < 20`).
    - Snake body is managed as a list of `turtle.Turtle()` objects.
    - Screen updates are manual (`wn.tracer(0)` and `wn.update()`) to ensure smooth animation.

## Project Structure

- `snake.py`: The main and only source file containing all game code.
- `README.md`: Basic user documentation and instructions.
- `GEMINI.md`: (This file) Instructional context for Gemini CLI.
- `AGENTS.md`: (This file) Instructional context for Gemini CLI.

