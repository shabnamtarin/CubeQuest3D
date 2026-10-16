# CubeQuest 3D

**CubeQuest 3D** is a 3D action-arcade survival game built with Python and OpenGL. Control a cubic player, collect shapes to earn points, avoid obstacles and enemies, and survive as the challenge increases across levels.

## Features

- **3D arcade gameplay** with a third-person camera
- **Collectibles and scoring** for collecting geometric shapes
- **Enemies and obstacles** that make each run more challenging
- **Multiple player types** with different special abilities
- **Power-ups** including speed boosts, temporary invincibility, freezing enemies, and double-score effects
- **Boss encounters** at set level intervals
- **Combo and score multiplier system**
- **Progressive difficulty** as the player advances
- **Dynamic day-night cycle** that changes the environment lighting and sky
- **Lives, health, levels, and score tracking**
- **Local leaderboard** that saves top scores to a JSON file

## Built With

- Python
- PyOpenGL (`OpenGL.GL`, `OpenGL.GLU`)
- GLUT (`OpenGL.GLUT`)

## Getting Started

### Prerequisites

Install Python and the required OpenGL packages. Depending on your operating system, GLUT/freeglut may also need to be installed separately.

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

Make sure a compatible GLUT/freeglut runtime is available on your system.

### Run the Game

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Run the main game source file:

```bash
python 3D_Game
```

If Python does not recognize the filename, rename the source file to `3D_Game.py` and run `python 3D_Game.py`, or use the exact filename saved in your local copy.

## Gameplay Overview

Move around the arena, collect geometric shapes, avoid hazards, and use your selected character's special ability at the right moment. Build combos to increase your score multiplier and progress through increasingly difficult levels.

## Project Structure

The repository currently contains:

```text
CubeQuest-3D/
├── 3D_Game       # Main game source file
└── README.md     # Project documentation
```

The game may create `scoreboard.json` locally when scores are saved. It is a runtime data file, so it does not need to be present in the repository before the game is run.

## Notes

- The leaderboard is stored locally in a JSON file.
- Check the source code or in-game menu for the exact controls.
- Run the game in your environment to confirm dependency and platform compatibility.

---

*This game was developed as a group project for the CSE423 course.*
