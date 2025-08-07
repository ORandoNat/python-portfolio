# Maze Runner 3D

**A terminal-based maze exploration game with pseudo-3D rendering.**  
Created by Al Sweigart • Adapted and documented by Nathan

---

## Project Description

Maze Runner 3D is a visually immersive command-line game that simulates a 3D maze using ASCII art. Players navigate through a maze from a first-person perspective, turning and moving forward to reach the exit. The game dynamically renders walls based on the player's position and orientation, creating a unique visual experience entirely within the terminal.

---

## Features

- 🧱 Perspective-based wall rendering using layered ASCII art
- 🧭 Directional movement with support for turning and forward motion
- 📂 Maze file loader with listing and validation
- 🧙 Cheat code support for teleporting to specific coordinates
- 🧵 Modular codebase with clear separation of rendering, input, and logic

---

## How to Play

1. Run the program:
   ```bash
   python maze3d.py
   ```

2. Enter the filename of a maze file, or type `LIST` to view available files.

3. Use the following controls during gameplay:

| Key        | Action                  |
|------------|--------------------------|
| `W` or `F` | Move forward             |
| `A` or `L` | Turn left                |
| `D` or `R` | Turn right               |
| `T x,y`    | Teleport to coordinates  |
| `QUIT`     | Exit the game            |

---

## Maze File Format

Maze files must be plain text and use the following characters:

| Character | Meaning        |
|-----------|----------------|
| `#`       | Wall           |
| (space)   | Empty space    |
| `S`       | Start position |
| `E`       | Exit position  |

Example:
```
##########
#S     E #
# ###### #
#        #
##########
```

---

## Code Structure

- `wallStrToWallDict()` – Converts ASCII wall drawings into coordinate-based dictionaries
- `pasteWallDict()` – Overlays wall segments onto the base wall view
- `makeWallDict()` – Builds the current wall view based on player position and direction
- `displayWallDict()` – Renders the wall dictionary to the terminal
- Main loop – Handles user input, movement logic, and win condition

---

## Requirements

- Python 3.x
- No external libraries required

---

## Acknowledgments

This project is based on Maze 3D from *The Big Book of Small Python Projects* by Al Sweigart.  
Maze files can be generated using `mazemakerrec.py` (not included).
