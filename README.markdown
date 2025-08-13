# Pong Game

A classic Pong game implemented in Python using the Turtle graphics library. Two players control paddles to bounce a ball back and forth, scoring points when the opponent misses the ball. The game features a simple scoreboard and smooth ball physics with increasing speed on paddle hits.

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

- **Paddle Movement**: Two players control paddles using keyboard inputs.
- **Ball Physics**: The ball bounces off paddles and top/bottom walls, with speed increasing slightly after each paddle hit.
- **Scoreboard**: Displays scores for both players at the top of the screen.
- **Simple Graphics**: Uses Turtle for rendering paddles, ball, and scoreboard on a black background.

## Files

- `game.py`: Main script for the Pong game, handling game loop and logic.
- `paddle.py`: Paddle class for creating and controlling paddles.
- `ball.py`: Ball class for ball movement and collision behavior.
- `scoreboard.py`: Scoreboard class for tracking and displaying player scores.

## Requirements

- Python 3.x
- Turtle module (included in standard Python library)

## How to Run

1. Ensure Python is installed on your system.
2. Clone the repository:
   ```bash
   git clone https://github.com/remi23242/Pong-Game.git
   ```
3. Navigate to the project directory:
   ```bash
   cd Pong-Game
   ```
4. Run the game:
   ```bash
   python game.py
   ```

## Controls

- **Right Paddle**:
  - **Up Arrow**: Move paddle up.
  - **Down Arrow**: Move paddle down.
- **Left Paddle**:
  - **W**: Move paddle up.
  - **S**: Move paddle down.

## Gameplay

- The game runs on an 800x600 screen with a black background.
- Two paddles are positioned at x=±350, controlled by players to hit a ball.
- The ball bounces off the top and bottom walls (y > 280 or y < -280) and paddles (within 50 units and x > 320 or x < -320).
- A point is scored when the ball passes a paddle (x > 380 or x < -380), resetting the ball to the center with a slight speed increase.
- The scoreboard updates and displays scores at (-100, 200) and (100, 200).
- The game continues until the window is clicked to exit.

## Future Improvements

- Add a game over condition (e.g., first player to reach 10 points wins).
- Implement a pause/restart feature.
- Add sound effects for paddle hits, wall bounces, and scoring.
- Introduce an AI opponent for single-player mode.
- Allow customization of paddle size or ball speed.

## License

This project is open-source and available under the MIT License.