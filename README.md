# Asteroids in Python

Asteroids is my second [Boot.dev](https://www.boot.dev) project!

Asteroids is a classic arcade game built using Python and the Pygame library. In this game, you control a spaceship and must shoot and avoid asteroids to survive.

## Certificate

<p align="center">
  <img width="832" height="508" alt="Boot.dev Certificate" src="https://github.com/user-attachments/assets/6febac4c-f9db-4f71-9b59-bdb953485553" />
</p>

## What I Learned

While building Asteroids, I practiced several advanced Python and game development concepts:

- **Object-Oriented Programming (OOP):** Using classes and inheritance to organize game objects like players, asteroids, and shots.
- **Pygame Library:** Implementing a game loop, handling user input, and rendering graphics.
- **Vector Math:** Using `pygame.Vector2` for movement, rotation, and calculating object trajectories.
- **Collision Detection:** Implementing circle-based collision logic to detect hits between game objects.
- **Sprite Groups:** Managing multiple game objects efficiently using Pygame's `Group` containers.
- **Game State Management:** Implementing logic for shooting, asteroid splitting, and game-over conditions.
- **Constants & Configuration:** Organizing game parameters in a dedicated configuration file for easy balancing.

## Usage

This project uses [uv](https://docs.astral.sh/uv/) for dependency management, but you can also use `pip` with the `requirements.txt` file.

### Option 1: Using uv (Recommended)

#### Setup Virtual Environment

```bash
# Create a virtual environment and install dependencies
uv sync
```

#### Activate Virtual Environment

```bash
# On macOS/Linux:
source .venv/bin/activate

# On Windows:
.venv\Scripts\activate
```

### Option 2: Using pip

```bash
# Install dependencies
pip install -r requirements.txt
```

### Run the game

```bash
python3 main.py
```

## Controls

- **Left/Right Arrows:** Rotate the spaceship.
- **Up Arrow:** Move forward.
- **Down Arrow:** Move backward.
- **Spacebar:** Shoot bullets.

## Output

```
Starting Asteroids with pygame version: 2.x.x
Screen width: 1280
Screen height: 720
Game over!
```
