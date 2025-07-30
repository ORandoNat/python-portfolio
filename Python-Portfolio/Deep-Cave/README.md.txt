# 🕳️ Deep Cave — ASCII Tunnel Animation

A mesmerizing animation of a never-ending descent into a rocky cave, rendered entirely in ASCII. Inspired by classic terminal art and dungeon crawler aesthetics, this simulation uses randomized tunnel shaping to mimic a shifting underground passage.

## 🌌 Features

- Dynamic cave walls shift frame-by-frame for endless movement
- Adjustable `WIDTH` and `PAUSE_AMOUNT` for different tunnel shapes and scroll speeds
- Uses random dice rolls to tweak wall and gap widths
- Quits cleanly on `Ctrl+C` input
- Great for terminal-based aesthetic displays or coding demos

## 🔧 Technologies Used

- Python 3
- Libraries: `random`, `sys`, `time`

## 🎮 How to Run

```bash
python deep_cave.py
```

Sit back and descend into the abyss. Press `Ctrl+C` to stop.

## 🧠 Learning Highlights

- Explored frame-based animation with pause control
- Applied random number generation to drive environmental variation
- Practiced string manipulation for layout rendering
- Developed consistent layout logic based on tunnel geometry
- Balanced performance with responsiveness using timed loops

## ✨ Customization Ideas

- Adjust `WIDTH` for narrower or wider tunnels
- Speed up or slow down animation with `PAUSE_AMOUNT`
- Use different characters (e.g., `|`, `.`, `█`) for visual experimentation
- Incorporate color with `colorama` or tunnel depth counters
- Expand to dungeon crawler base for a future game project
