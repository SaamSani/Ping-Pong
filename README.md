# 🏓 Pong Game

This repository contains a Python implementation of the classic Pong game using the `turtle` module. Engage in a head-to-head battle to score points by bouncing the ball past your opponent!

## Features

- **Classic Gameplay**: Play a two-player game controlling paddles to hit the ball.
- **Score Tracking**: Keeps track of left and right players' scores.
- **Realistic Physics**: Ball bounces off walls and paddles, with increasing speed for added challenge.
- **Customizable**: Modify paddle sizes, ball speed, and screen dimensions.

## Files Overview

### Source Code

- **`main.py`**: The entry point of the game, handles the game flow, paddle controls, and collisions.
- **`paddle.py`**: Contains the `Paddle` class, which defines paddle movement and initialization.
- **`ball.py`**: Implements the `Ball` class, handling movement, bouncing mechanics, and resets.
- **`scoreboard.py`**: Defines the `Scoreboard` class to display and update scores.

### Compiled Files

- **`.pyc files`**: Precompiled Python files for faster execution.

## How to Play

1. **Run the game**: Execute `main.py` in your Python environment.
2. **Control the paddles**:
   - Right paddle:
     - Move up: Press the `Up` arrow key.
     - Move down: Press the `Down` arrow key.
   - Left paddle:
     - Move up: Press the `W` key.
     - Move down: Press the `S` key.
3. **Objective**:
   - Score points by hitting the ball past your opponent's paddle.
4. **Game Over**: Continue playing until one player decides to quit.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pong-game.git
   cd pong-game
