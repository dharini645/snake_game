# 🐍 Snake Game

A classic Snake game built with Python using the `turtle` graphics module. Eat food to grow longer, avoid the walls and your own tail, and beat your high score!

## Demo

```
 ___________________________
|  Score: 5 | High Score:   |
|        🟢                 |
|                           |
|     ████████              |
|             █             |
|             █             |
|___________________________|
         
```

## Features

- Smooth snake movement with arrow key controls
- Food spawns at random positions on the screen
- Score tracking that increases with each food eaten
- High score persistence — your best score is saved to `data.txt` and carried across sessions
- Wall and self-collision detection with automatic game reset

## Project Structure

```
snake_game/
├── main.py          # Game loop and collision detection
├── snake.py         # Snake class — movement, growth, and reset logic
├── food.py          # Food class — random placement on the screen
├── scoreboard.py    # Scoreboard class — score display and high score saving
└── data.txt         # Persistent high score storage
```

## Requirements

- Python 3.x
- `turtle` module (included in the Python standard library — no install needed)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/dharini645/snake_game.git
   cd snake_game
   ```

2. Run the game:
   ```bash
   python main.py
   ```

## Controls

| Key | Action |
|-----|--------|
| ↑ Up Arrow | Move Up |
| ↓ Down Arrow | Move Down |
| ← Left Arrow | Move Left |
| → Right Arrow | Move Right |

## How to Play

- Use the arrow keys to steer the snake around the screen.
- Eat the food (red dot) to grow longer and increase your score.
- Avoid hitting the walls or running into your own tail.
- When you collide, the snake resets but your high score is saved!

## Author

**Dharini** — [GitHub](https://github.com/dharini645)
