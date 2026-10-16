[README.md](https://github.com/user-attachments/files/33583015/README.md)
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
- **Local leaderboard** that stores top scores in `scoreboard.json`

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
3. Run the Python game file:

```bash
python 3D_Game.py
```

If the Python source file in the repository has a different name, replace `3D_Game.py` with that filename.

## Gameplay Overview

Move around the arena, collect geometric shapes, avoid hazards, and use your selected character's special ability at the right moment. Build combos to increase your score multiplier and progress through increasingly difficult levels.

## Project Structure

```text
CubeQuest-3D/
├── 3D_Game.py
├── scoreboard.json
└── README.md
```

The leaderboard file may be created automatically when the game saves scores. Adjust the file names in this diagram to match the files in your repository.

## Notes

- The game uses a local JSON file for leaderboard persistence.
- Check the source code or in-game menu for the exact controls.
- Run the game in your environment to confirm dependency and platform compatibility.

---

*This game was developed as a group project for the CSE423 course.*
