# 2-Player Pong

A simple local 2-player Pong game built using Python and Pygame.

This project extends the original simple Pong game by Baris Bayrak (garib) on pygame.org, adding second-player controls and a "First to 11, Win by 2" victory condition.

## Features

- **Local Multiplayer:** Play against another player on the same keyboard.
- **Color-Coded Paddles:** Blue paddle (left) vs. Red paddle (right).
- **Scoreboard:** Real-time scores displayed on screen.
- **Victory Condition:** First to 11 points (must win by 2).

## Controls

| Player | Up | Down |
| :--- | :--- | :--- |
| **Blue (Left)** | `W` | `S` |
| **Red (Right)** | `Up Arrow` | `Down Arrow` |

## Getting Started

### Installation

1. Install Pygame:
   ```bash
   pip install pygame
   ```

2. Run the game:
   ```bash
   python PONG_GAME.py
   ```

> [!NOTE]
> The code uses Python 2 `raw_input` to pause the game at the end. Under Python 3, this line will cause an error when the game finishes unless updated to `input()`.

## Credits

- **Original Creator:** Baris Bayrak (garib)
- **Original Source:** [pygame.org Project Page](http://www.pygame.org/project-Very+simple+Pong+game-816-.html)
