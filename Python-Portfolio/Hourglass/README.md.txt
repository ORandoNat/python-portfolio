# ⏳ Hourglass — Sand Simulation in Python Terminal

An ASCII-based animation that simulates falling sand inside an hourglass, built using the `bext` module for terminal graphics. Watch grains cascade and settle inside walls crafted from Unicode blocks in real time.

## 🎯 Objective

Visually represent an hourglass where grains of sand fall, settle, and eventually reset — all from the command line. The simulation mimics gravity, collision detection, and randomness in particle movement.

## 🛠️ Features

- Full hourglass rendered with Unicode box characters
- Realistic sand behavior: fall, slide, bounce left/right
- Configurable simulation parameters (pause speed, spread chance)
- Dynamic display using the `bext` module
- Automatically resets after sand settles
- Graceful exit using `Ctrl+C`

## 🚀 How to Run

1. Install the `bext` module:

```bash
pip install bext
```

2. Run the script:

```bash
python hourglass.py
```

Watch the sand fall and reset in cycles — endlessly hypnotic.

## ⚙️ Configurable Parameters

| Variable         | Description                                |
|------------------|--------------------------------------------|
| `PAUSE_LENGTH`   | Time between frame updates (default: `0.2`)|
| `WIDE_FALL_CHANCE`| Percent chance of sand falling farther    |
| `SCREEN_WIDTH`   | Width of the display (default: `79`)       |
| `SCREEN_HEIGHT`  | Height of the display (default: `25`)      |

## ✏️ Learning Highlights

- Used terminal coordinate control via `bext.goto(x, y)`
- Applied sand collision physics with neighbor checks
- Introduced pseudo-random directionality for natural movement
- Designed map layout using sets of `(x, y)` tuples
- Implemented automatic reset logic when simulation completes

## 💡 Extension Ideas

- Add color variation for top and bottom chambers
- Track how long a full drain takes and print stats
- Control hourglass refill speed or direction (reverse flow!)
- Turn into a screensaver-style effect
- Record a GIF of the animation for showcase

## 🎨 ASCII Materials

| Symbol | Description |
|--------|-------------|
| `░` (U+9617) | Sand grain  |
| `█` (U+9608) | Wall block  |
