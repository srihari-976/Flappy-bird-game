# Flappy Bird Game

Flappy Bird is a classic arcade-style game where you navigate a bird through a series of pipes without hitting them. This implementation of Flappy Bird is built using Python and Pygame.

## Game Description

The objective of the game is to navigate the bird through the gaps in the pipes by pressing the spacebar or the up arrow key to make the bird flap. The player scores points by passing through the gaps in the pipes.

## Features

- **Welcome Screen:** Displays a welcome screen before the game starts.
- **Game Mechanics:** Handles player movement, collision detection, scoring, and pipe generation.
- **Sound Effects:** Includes sound effects for wing flaps, points, collisions, and game over.
- **Graphics:** Uses sprites for the bird, pipes, background, and numbers.

## Installation

### Prerequisites

- Python 3.x
- Pygame

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/srihari-976/Flappy-bird-game.git
   cd Flappy-bird-game

2. **Install Dependencies:**:

   ```bash
   pip install pygame

3. **Ensure you have the necessary images and audio files in the gallery/sprites and gallery/audio directories, respectively.


### Usage

1. **Run the Game**:

   ```bash
   python flappybird.py

2. **Play the Game**:
   
   - Press the Space key or the Up arrow key to make the bird flap.
   - Navigate the bird through the pipes without hitting them.
   - The game will display your score and play sound effects as you progress.

 ### Game Assets
- **Bird Sprite:** gallery/sprites/bird.png
- **Background Image:** gallery/sprites/background.png
- **Pipe Image:** gallery/sprites/pipe.png
- **Number Sprites:** gallery/sprites/0.png, 1.png, ..., 9.png
- **Message Image:** gallery/sprites/message.png
- **Base Image:** gallery/sprites/base.png
- **Audio Files:** gallery/audio/die.wav, hit.wav, point.wav, swoosh.wav, wing.wav     
