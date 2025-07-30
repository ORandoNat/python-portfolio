# 🧬 Conway's Game of Life — Terminal Cellular Automata

A Python-based simulation of Conway's Game of Life — a zero-player game where cells on a grid live, die, or reproduce based on a set of simple rules. This implementation generates an evolving ASCII-based world of "living" and "dead" cells that interact over time in mesmerizing ways.

## 🌱 Concept Overview

Conway’s Game of Life follows these rules:
1. A live cell with 2 or 3 live neighbors survives.
2. A dead cell with exactly 3 live neighbors becomes alive.
3. All other cells die or remain dead.

Despite its simplicity, this system gives rise to incredibly complex and emergent behaviors — a classic staple in simulations and computational theory.

- [Wikipedia: Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)

## 🛠️ Features

- Terminal-based animation of a randomly seeded grid
- Configurable cell size (via `WIDTH` and `HEIGHT`)
- Wraparound grid boundaries for continuous flow
- Uses character symbols to represent alive (`O`) and dead (` `) cells
- Graceful quit with `Ctrl+C`

## 🚀 Technologies Used

- Python 3
- Libraries: `random`, `time`, `sys`, `copy`

## 🧠 Learning Highlights

- Practiced grid indexing and neighbor detection
- Used modular arithmetic for edge wrapping
- Implemented Conway’s logic through dictionary state updates
- Employed deep copy to preserve generation snapshots
- Controlled output pacing with timed display

## 📦 How to Run

```bash
python game_of_life.py
```

Observe the simulation animate in your terminal. Press `Ctrl+C` to exit.

## 🔄 Customization Ideas

- Change characters (`ALIVE`, `DEAD`) for creative designs
- Add pattern seed options (gliders, oscillators, etc.)
- Increase frame rate or smooth transitions with `curses` or `colorama`
- Save each generation’s state to files for analysis or replay
- Write test functions to validate cell evolution logic (QA-relevant)
