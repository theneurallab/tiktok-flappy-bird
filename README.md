# Flappy Bird Game

A classic Flappy Bird game implementation using Python and Pygame.

## Requirements

- Python 3.6+
- Pygame library

## Steps to Run this Codebase

1. Fork this repository: `https://github.com/theneurallab/tiktok-flappy-bird.git`
2. Clone your forked repository (replace `YOUR_USERNAME` with your actual GitHub username):

```bash
git clone https://github.com/YOUR_USERNAME/tiktok-flappy-bird.git
```

3. Navigate to the project directory:

```bash
cd tiktok-flappy-bird
```

4. Run the game:

```bash
python main.py
```

## Game Controls:

- **Mouse Click**: Make the bird jump/flap
- **ESC or Q**: Quit game
- **Click on Start Screen**: Start the game
- **Click on Game Over**: Restart the game

## Game Rules:

- Control the bird by clicking to make it flap and avoid pipes
- Navigate through the gaps between pipes to score points
- Each successful pipe passage earns you one point
- Game over when the bird hits a pipe, the ground, or the ceiling

## Project Structure

```
tiktok-flappy-bird/
├── main.py                 # Main game loop and logic
├── objects.py              # Game object classes (Bird, Pipe, Base, Score)
├── assets/                 # Game graphics
│   ├── background-day.png
│   ├── background-night.png
│   ├── base.png
│   ├── flappybird.png
│   ├── gameover.png
│   ├── pipe-green.png
│   ├── pipe-red.png
│   ├── grumpy/            # Bird animation frames
│   │   ├── blue1.png, blue2.png, blue3.png
│   │   ├── red1.png, red2.png, red3.png
│   │   └── yellow1.png, yellow2.png, yellow3.png
│   └── score/             # Number sprites for scoring
│       └── 0.png - 9.png
├── audio/                 # Sound effects
│   ├── die.wav
│   ├── hit.wav
│   ├── point.wav
│   ├── swoosh.wav
│   └── wing.wav
└── README.md              # Project documentation
```

Made with ❤️ by [Neural Lab](https://theneurallab.com)
