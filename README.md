# Snake Game

This is a classic Snake game implemented using Pygame.

## How to Install

1. Clone the repository:
```bash
git clone git@github.com:alecgrater/Snake.git
```

2. Navigate to the project directory:
```bash
cd Snake
```

3. Install the required dependencies:
```bash
pip install pygame
```


## How It Works

The game consists of a snake that moves around the screen and tries to eat food to grow longer. The objective is to prevent the snake from colliding with its own body or the game boundaries.

The snake is controlled using the arrow keys (up, down, left, right). Each time the snake eats food, its length increases, and the score is incremented. The game ends if the snake collides with itself or the boundaries.

### Snake Class

The `Snake` class represents the snake in the game. It keeps track of the snake's length, positions, direction, color, and score. The class provides methods for moving the snake, handling user input, and drawing the snake on the screen.

### Food Class

The `Food` class represents the food that the snake tries to eat. It has a position and a color that are randomly generated each time the snake eats the food. The class provides a method for drawing the food on the screen.

### Game Loop

The game follows a main loop that repeatedly updates the game state, handles user input, and redraws the screen. The loop runs at a fixed frame rate to control the speed of the game.

Enjoy playing the Snake game!

