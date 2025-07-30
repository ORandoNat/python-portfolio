# 🐠 Fish Tank — Animated ASCII Aquarium in Terminal

A peaceful, dynamic fish tank simulation built with colorful ASCII art, moving fish, waving kelp, and rising bubbles — all rendered in your terminal using the `bext` module. Inspired by ASCIIQuarium and EmojiAquarium, this project recreates underwater serenity in code.

## 🌊 Features

- Dozens of distinct fish types with animated direction and colors
- Fish swim across the screen with realistic vertical and horizontal movement
- Bubbles rise from randomized "bubblers" at the bottom of the tank
- Kelp sways gently to simulate underwater motion
- Sand substrate rendered at the bottom for environment realism
- Smooth frame transitions controlled by adjustable framerate
- Terminal-based graphics using colored cursor placement (`bext`)
- Graceful exit on `Ctrl+C`

## 🎮 How It Works

- **Fish:** Each has direction, speed, colors, and body types (via ASCII strings)
- **Bubbles:** Spawn randomly from bubblers and float upwards, swaying left/right
- **Kelp:** Generated with random segments that toggle shape to simulate movement
- **Rendering:** Terminal cursor is moved for precise control, colors assigned per character

## 📦 Requirements

- **Python 3**
- [`bext` module](https://pypi.org/project/Bext/)

```bash
pip install bext
```

## 🚀 How to Run

```bash
python fish_tank.py
```

Watch the tranquil aquatic scene unfold in your terminal.

## ⚙️ Configuration Parameters

You can adjust these constants to personalize your tank:

| Constant            | Description                                |
|---------------------|--------------------------------------------|
| `NUM_FISH`          | Number of fish in the tank                 |
| `NUM_KELP`          | Number of kelp strands                     |
| `NUM_BUBBLERS`      | Number of bubble sources                   |
| `FRAMES_PER_SECOND` | Controls animation speed                   |

## 🧠 Learning Highlights

- Used object dictionaries to control fish attributes and behaviors
- Implemented frame-based animation logic using loops and timers
- Mastered terminal cursor management with `bext`
- Practiced event-driven rendering and cleanup routines
- Simulated multi-entity environments with coordinated timing

## 🎨 Extension Ideas

- Add collision detection or fish interactivity
- Enable feeding logic or spawning behavior
- Import aquatic-themed sounds for ambience
- Extend to a full terminal-based aquarium game
- Write automated tests for fish behavior and screen updates