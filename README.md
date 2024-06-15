# Flappy Bird Clone

This project is a clone of the popular Flappy Bird game built using Python and Pygame. The objective of the game is to navigate the bird through a series of pipes without hitting them.

## Installation

To run this project, you need to have Python and Pygame installed on your machine.

1. **Install Python**: You can download Python from [python.org](https://www.python.org/).

2. **Install Pygame**: Once you have Python installed, you can install Pygame using pip. Open your command line or terminal and run:
    ```
    pip install pygame
    ```

## How to Run

1. Clone the repository or download the source code.
2. Ensure all images are placed in an `img` folder within the same directory as the script.
3. Run the script:
    ```
    python main.py
    ```

## Game Controls

- **SPACE**: Start the game / Flap the bird
- **R**: Restart the game after a collision

## Game Mechanics

### Bird

- The bird is controlled by the player and it falls due to gravity.
- Pressing the SPACE key makes the bird flap and rise.

### Pipes

- Pipes appear from the right side of the screen and move to the left.
- The player must navigate the bird through the gaps in the pipes.

### Ground

- The ground scrolls continuously to give the illusion of movement.

### Score

- The score increases each time the bird successfully passes through a pair of pipes.

### Collision Detection

- The game ends if the bird collides with a pipe or the ground.
- Upon collision with the ground, a "Game Over" screen is displayed, and the player can restart by pressing the R key.

## Code Overview

### Main Components

1. **Bird Class**: Handles bird animation, movement, and collisions.
2. **Pipe Class**: Manages pipe creation, movement, and scoring.
3. **Ground Class**: Handles the scrolling ground effect.
4. **Main Game Loop**: Manages game state, drawing, and updating of game objects.
5. **Menu Function**: Displays the start screen and waits for user input to begin the game.

### Key Variables

- `win_height`, `win_width`: Dimensions of the game window.
- `scroll_speed`: Speed at which the pipes and ground scroll.
- `bird_start_position`: Initial position of the bird.
- `score`: The current score of the player.
- `font`: Font used for displaying the score.

## Acknowledgements

- Pygame for providing the game development framework.
- The original Flappy Bird game for inspiring this project.


Enjoy the game and happy coding!
