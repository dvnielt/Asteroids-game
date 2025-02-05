# Asteroids Game

A modern Python implementation of the classic Asteroids arcade game using Pygame.

## Features
- Smooth player movement with rotation and thrust
- Dynamic asteroid spawning and splitting mechanics
- Collision detection system
- Shooting mechanics with cooldown

## Requirements
```
pygame==2.6.0
```

## Installation
1. Clone the repository:
```bash
git clone [repository-url]
cd asteroids-game
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Play
Run the game:
```bash
python main.py
```

### Controls
- `W` - Thrust forward
- `S` - Thrust backward
- `A` - Rotate left
- `D` - Rotate right
- `SPACE` - Shoot

## Game Mechanics
- Player controls a triangular spaceship in a 2D space
- Asteroids spawn from screen edges
- Shooting asteroids splits them into smaller pieces
- Game ends if player collides with an asteroid

## Project Structure
- `main.py`: Game initialization and main loop
- `player.py`: Player ship controls and mechanics
- `asteroid.py`: Asteroid behavior and splitting logic
- `shot.py`: Projectile mechanics
- `constants.py`: Game configuration
- `circleshape.py`: Base class for circular collision objects

## Configuration
Adjust game settings in `constants.py`:
- Screen dimensions
- Player movement speed
- Shooting cooldown
- Asteroid spawn rate
- Object sizes

## Contributing
Feel free to fork, open issues, or submit PRs.

## License
[Your chosen license]
