# 🔥 Forest Fire Sim — Terminal-Based Wildfire Model

A terminal-based visualization of wildfire dynamics in a forest. Inspired by Nicky Case’s explorable simulations, this project models how trees grow, burn, and vanish in a grid environment using probabilistic rules.

## 🌲 Simulation Overview

The simulation operates as a simple cellular automaton:

- `A` = Tree 🌳  
- `W` = Fire 🔥  
- `' '` = Empty space

### Simulation Rules:

1. Trees can grow in empty spaces based on `GROW_CHANCE`.
2. Trees may ignite due to lightning (`FIRE_CHANCE`).
3. Fire spreads to nearby trees (including diagonals).
4. Burning trees become empty spaces next step.

## 🛠️ Features

- Adjustable parameters for tree density, growth, fire chance, and speed
- Real-time forest display using colored ASCII characters
- Modular functions for simulation, rendering, and state transitions
- Graceful exit using `Ctrl+C`
- Uses `bext` for colored terminal output

## 📦 Requirements

- Python 3
- [`bext`](https://pypi.org/project/Bext/) library

```bash
pip install bext
```

## 🚀 How to Run

```bash
python forest_fire_sim.py
```

Watch the forest evolve and burn — or adjust the parameters to control the chaos.

## ⚙️ Configurable Parameters

| Constant             | Description                            |
|----------------------|----------------------------------------|
| `WIDTH`              | Width of forest grid                   |
| `HEIGHT`             | Height of forest grid                  |
| `INITIAL_TREE_DENSITY` | Percentage of starting grid with trees |
| `GROW_CHANCE`        | Chance for empty space to grow a tree  |
| `FIRE_CHANCE`        | Chance for tree to catch fire (lightning) |
| `PAUSE_LENGTH`       | Time between frames                    |

## 🧠 Learning Highlights

- Modeled event-driven environmental simulation
- Applied grid-based update logic and neighbor evaluation
- Practiced dictionary-based spatial data modeling
- Used structured display logic with modular `bext` styling
- Explored emergent behaviors from simple rules

## 🔧 Extension Ideas

- Add wind direction to influence fire spread
- Visualize recovery/ash stages with new symbols
- Export simulation data for graphing or analysis
- Build a GUI version with `tkinter` or `pygame`
- Write QA tests for forest generation and spread logic