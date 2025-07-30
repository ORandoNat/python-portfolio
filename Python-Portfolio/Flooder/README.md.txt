# 🌈 Flooder — Terminal-Based Flood Fill Puzzle Game

A vibrant and colorfully chaotic tile-flood game that challenges you to unify a board with a single tile type. Inspired by "Flood It!", this project features color mode and shape-based accessibility for colorblind players, plus clean recursion-driven gameplay.

## 🧠 Objective

You start in the upper-left corner. On each move, you select a tile type to flood-fill adjacent matching tiles. Can you make the entire board match before your moves run out?

## 🖼️ Features

- Terminal-based colored tile display using the `bext` module
- Option to play in colorblind shape mode:
  - Shapes: ♥ ▲ ♦ • ♣ ♠
- Choose from multiple vibrant colors (or shapes) each turn
- Recursively flood-fills connected tile regions
- Victory if all tiles match before moves run out
- Framed board with decorative borders for clarity

## 🚀 How to Run

Requires the [`bext`](https://pypi.org/project/bext/) module:

```bash
pip install bext
python flooder.py
```

Follow the prompts to pick a display mode and start flooding.

## 🎮 Controls

| Mode         | Available Moves                       |
|--------------|----------------------------------------|
| Color Mode   | R, G, B, Y, C, P (Red → Purple)        |
| Shape Mode   | H, T, D, B, C, S (♥ → ♠)               |
| Other        | QUIT to exit                          |

Each move floods from the upper-left to surrounding matching tiles.

## 🧠 Learning Highlights

- Applied recursive flood-fill algorithm across grid
- Used dictionaries and coordinate tuples for tile mapping
- Integrated accessibility features (shape mode)
- Managed real-time terminal colors with `bext.fg()`
- Practiced input validation and state management

## ⚙️ Game Settings

Easily tweak the game difficulty or board design:

| Constant         | Effect                             |
|------------------|------------------------------------|
| `BOARD_WIDTH`    | Horizontal size of game board      |
| `BOARD_HEIGHT`   | Vertical size of game board        |
| `MOVES_PER_GAME` | Number of moves allowed            |

## 🔧 Extension Ideas

- Add animation effects or sound alerts
- Save game state and track score history
- Add player-defined themes (custom shape/color sets)
- Convert into multiplayer or timed challenge mode
- Write unit tests to validate recursive flood behavior
