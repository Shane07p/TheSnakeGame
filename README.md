# TheSnakeGame
TheSnakeGame Project by Team Codestrikers

This is a simple console-based Snake game implemented in C++. The game features a dynamic board, food spawning, and snake movement controlled via keyboard inputs. The player navigates the snake to eat food and grow while avoiding collisions with the walls.


## Features

- Board Setup: The game runs on a fixed-size board with defined boundaries.

- Snake Movement: The snake can move in four directions (Up, Down, Left, Right) using arrow keys or W/A/S/D keys.

- Food Mechanics: The food spawns randomly on the board and relocates when consumed by the snake.

- Difficulty Levels: Players can choose from Easy, Medium, or Hard difficulty settings, affecting snake speed.

- Score Tracking: The game tracks and displays the player's current and highest score. It stores the high score of a unique ID.

- Obstacles: The game spawns obstacles randomly and its position changes over the time and number of obstacles increase as level increase.

- Pause: On pressing 'p' game will pause and pressing 'r' game will resume.
  
## Controls

- Arrow Keys or WASD: Move the snake

- Game Over Condition: The game ends if the snake collides with the board boundaries or collides with itself.
## How To Run

1. Compile the program using a C++ compiler (MinGW/GCC recommended):

```bash
  g++ snake_game.cpp -o snake_game
```
2. Run
```bash
  snake_game.exe
```

## Dependencies

- The game requires windows.h for console manipulation and bits/stdc++.h for standard library usage.

- It is intended for Windows OS due to the use of Sleep() and GetAsyncKeyState() functions.
  
- We also used SetConsoleTextAttribute() from windows.h to set colors for objects.
  
## Authors

- Shane Christian
- Bansil Bhanderi
- Pranshu Chovatiya
- Hari Patel


## License

- This project is open-source and free to use.

