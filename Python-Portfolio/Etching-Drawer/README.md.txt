# 🖋️ Etching Drawer — WASD-Based Terminal Art Program

A playful terminal drawing tool inspired by the classic Etch A Sketch toy. This program allows users to sketch continuous line art using `W`, `A`, `S`, `D` keys, rendering beautiful patterns in real-time with Unicode box-drawing characters.

## 🧱 Features

- Draw freely using directional input
- Supports complex patterns like Hilbert Curves
- Visual cursor marker (`#`) for position tracking
- Auto-selection of appropriate box-drawing characters based on movement
- Save artwork and movement history to `.txt` files
- Clear canvas or view help prompts during runtime

## 🎮 Controls

| Key | Action             |
|-----|--------------------|
| `W` | Move up            |
| `A` | Move left          |
| `S` | Move down          |
| `D` | Move right         |
| `H` | Display help       |
| `C` | Clear canvas       |
| `F` | Save artwork       |
| `QUIT` | Exit the program |

## 🚀 How to Run

```bash
python etching_drawer.py
```

Follow the prompt and start drawing! Your sketch updates instantly.

## ✨ Examples

You can draw complex fractals like the **Hilbert Curve** using sequences like:
```
SDWDDSASDSAAWASSDSASSDWDSDWWAWDDDSASSDWDSDWWAWDWWASAAWDWAWDDSDW
```

## 🧠 Learning Highlights

- Built a stateful rendering engine using a dictionary with directional sets
- Applied box-drawing character logic based on movement combinations
- Managed screen dimensions and cursor movement safely
- Implemented input parsing and command interpretation
- Enabled canvas persistence with save/load feature

## 🛠 Technologies Used

- Python 3
- Libraries: `shutil`, `sys`

## 📁 File Output

Saved files include:
- Movement string (WASD history)
- Final canvas artwork with drawn lines

## 🧪 QA-Friendly Enhancements

- Add unit tests for canvas character resolution
- Refactor to separate rendering and input logic
- Expand to include undo/redo functionality
- Integrate pattern recognition or path validation

