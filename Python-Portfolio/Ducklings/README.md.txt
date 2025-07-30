# 🐥 Duckling Screensaver — Terminal Parade of Cuteness

A terminal-based animated screensaver that populates your screen with randomly generated ducklings waddling across in all their quirky glory. Built with object-oriented principles and ASCII charm, this project displays ducklings with randomized features including direction, body type, mood, wings, and eyes.

## ✨ Features

- Procedural generation of ducklings with diverse attributes:
  - Direction: `left` or `right`
  - Body: `chubby` or `very chubby`
  - Eyes: `beady`, `wide`, `happy`, `aloof`
  - Wing position: `up`, `down`, `out`
  - Mouth: `open` or `closed`
- Scrolling multi-line animation with real-time rendering
- Graceful shutdown via `Ctrl+C`
- Configurable speed and density

## 🚀 How to Run

```bash
python duckling_screensaver.py
```

Sit back and enjoy the duck parade. Press `Ctrl+C` to end the fun.

## 🛠 Technologies Used

- Python 3
- Standard libraries: `random`, `shutil`, `sys`, `time`

## 🧠 Learning Highlights

- Practiced class-based architecture to encapsulate behavior (`Duckling`)
- Used object attributes to dynamically generate visual character traits
- Controlled animation flow using timed main loops and terminal flush
- Handled conditional rendering based on current drawing state
- Balanced structure and performance for smooth scrolling visuals

## ⚙️ Configuration Parameters

| Constant     | Description                                 |
|--------------|---------------------------------------------|
| `PAUSE`      | Speed of animation (lower is faster)         |
| `DENSITY`    | Probability of duckling appearance per lane  |
| `DUCKLING_WIDTH` | Width of each duckling sprite in characters |

## 🎨 Customization Ideas

- Add color via `colorama` for playful palettes
- Expand feature sets (e.g., hats, accessories, dance moves!)
- Create seasonal variants (e.g., penguins, reindeer)
- Write unit tests for `Duckling` rendering consistency
- Export snapshots of the parade for display or artwork

