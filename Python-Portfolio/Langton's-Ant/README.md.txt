# 🐜 Langton's Ant — Terminal-Based Cellular Automaton Simulation

A mesmerizing terminal-based animation of Langton’s Ant, implemented in Python using the `bext` module. This project simulates multiple ants navigating a toroidal grid, flipping tile states and creating emergent patterns through simple deterministic rules.

## 🧠 Objective

Visualize the core principles of Langton’s Ant — a two-dimensional Turing machine:
- Ants move on a grid of black and white tiles
- Each ant turns right on black, left on white
- After moving, they flip the tile’s color
- The grid wraps at edges to form a toroidal world

This model demonstrates how simple rules can lead to unpredictable, chaotic behavior — even producing stable “highways” over time.

## 🛠️ Features

- Console-based animation with real-time updates using `bext`
- Multi-ant simulation with customizable behavior
- Dynamic cell coloring and direction-specific ant icons (`^`, `v`, `<`, `>`)
- Tile state memory and redraw efficiency via `changedTiles`
- Grid wrap-around to avoid boundary constraints
- Pause control for animation pacing

## 🚀 How to Run

Ensure `bext` is installed:

```bash
pip install bext
```

Then run the simulation:

```bash
python langtons_ant.py
```

Press **Ctrl+C** anytime to gracefully quit.

## 🐜 Ant Behavior Rules

| Tile Color      | Turn Direction | Tile Flip Result   |
|-----------------|----------------|--------------------|
| White (`False`) | Left           | Turns Black (`True`) |
| Black (`True`)  | Right          | Turns White (`False`) |

Ants move forward after turning. The simulation wraps at screen edges.

## ⚙️ Configurable Constants

| Constant         | Description                                |
|------------------|--------------------------------------------|
| `NUMBER_OF_ANTS` | Number of ants in the simulation           |
| `PAUSE_AMOUNT`   | Delay (seconds) between animation frames   |
| `ANT_COLOR`      | Foreground color of ants (`red`, etc.)     |
| `ANT_*`          | Symbols for directional representation     |
| `WHITE_TILE`     | Initial background color of tiles          |
| `BLACK_TILE`     | Color of flipped tiles (visited)           |

Grid size auto-adjusts to terminal dimensions via `bext.size()`.

## 🧠 Learning Highlights

- Practical use of terminal graphics via `bext`
- Directional logic with clockwise/counterclockwise rotation
- Efficient screen updates using state tracking and minimal redraws
- Modular ant behavior with random spawning and movement
- Wrap-around mechanics for bounded grid traversal

## 🔧 Extension Ideas

- Assign unique colors to each ant for path tracking
- Add heatmaps of visited tiles or movement history
- Convert to a GUI-based version using `pygame` or `tkinter`
- Implement pause/resume functionality or step-by-step mode
- Log grid states to file for replay or analysis
