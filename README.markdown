# Turtle Crossing Game

A Python-based game inspired by the classic Frogger, where a player controls a turtle to cross a busy road while avoiding cars. The game uses the Turtle graphics library for rendering. This repository also includes files for a Pong game as a bonus or reference implementation.

Note: The Turtle Crossing game code is in an initial state with some classes as stubs (e.g., `Player` and `CarManager`). It can be extended to add car generation, movement, collision detection, and level progression. The Pong game is more complete and can be run independently.

## Table of Contents
- [Features](#features)
- [Files](#files)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Controls](#controls)
- [Gameplay](#gameplay)
- [Future Improvements](#future-improvements)
- [License](#license)

## Features
- **Player Movement**: Control the turtle to move forward across the road.
- **Car Management**: (Stub) Generate and move cars at increasing speeds.
- **Scoreboard**: Displays scores (adapted from Pong; can be modified for levels in Crossing).
- **Simple Graphics**: Uses Turtle for rendering the player, cars, and scoreboard.
- **Bonus Pong Game**: A complete Pong game with paddles, ball, and scoring.

## Files
- `main.py`: Main game loop for Turtle Crossing.
- `player.py`: Player class for the turtle (currently a stub).
- `car_manager.py`: CarManager class for handling cars (currently a stub).
- `scoreboard.py`: Scoreboard class for displaying scores (shared/adapted for both games).
- `ball.py`: Ball class for the Pong game.
- `game.py`: Main script for the Pong game.
- `paddle.py`: Paddle class for the Pong game.
- `data.txt`: (If applicable from previous projects) Stores high scores or data.

## Requirements
- Python 3.x
- Turtle module (included in standard Python library)

## How to Run
1. Ensure Python is installed on your system.
2. Clone the repository:
   ```bash
   git clone https://github.com/remi23242/Turtle-Crossing-Game.git
   ```
3. Navigate to the project directory:
   ```bash
   cd Turtle-Crossing-Game
   ```
4. Run the Turtle Crossing game (note: extend the stubs for full functionality):
   ```bash
   python main.py
   ```
   Or run the Pong game:
   ```bash
   python game.py
   ```

## Controls
For Turtle Crossing (extend as needed):
- **Up Arrow**: Move the turtle forward.

For Pong:
- **W/S**: Left paddle up/down.
- **Up/Down Arrows**: Right paddle up/down.

## Gameplay
- In Turtle Crossing: Guide the turtle across the road without hitting cars. Reach the finish line to advance levels, with cars speeding up.
- In Pong: Two paddles bounce a ball back and forth. Score points when the opponent misses the ball.
- The game loop updates the screen and handles basic logic, but extend for collision detection and game over conditions.

## Future Improvements
- Complete the `Player` and `CarManager` classes for full Turtle Crossing functionality (e.g., random car generation, collision checks, level increases).
- Adapt the scoreboard for levels in Turtle Crossing instead of left/right scores.
- Add sound effects and a game over screen.
- Introduce power-ups or additional obstacles.

## License
This project is open-source and available under the MIT License.