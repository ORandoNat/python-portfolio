# 🧬 DNA — Double Helix Terminal Animation

A simple yet captivating terminal animation that mimics the twisting structure of a DNA double helix. Inspired by terminal-based visualizations, this project scrolls base pair strands across the screen using randomized nucleotide combinations and layered ASCII art.

## 🔧 Features

- Real-time scrolling of a rotating DNA strand
- Randomly selected base pairs (A–T, T–A, C–G, G–C)
- Adjustable scrolling speed via `PAUSE` constant
- Multiple helix curvature stages for visual fidelity
- Graceful interruption via `Ctrl+C`

## 🛠 Technologies Used

- Python 3
- Libraries: `random`, `time`, `sys`

## 🚀 How to Run

```bash
python dna.py
```

Watch the double helix come to life in your terminal. Press `Ctrl+C` to stop.

## 🧠 Learning Highlights

- Modeled biological pairings via randomized logic
- Built a wave-like structure using offset ASCII templates
- Managed terminal spacing and character placement dynamically
- Practiced frame-based rendering with loop control
- Explored art-meets-science in coding output

## ⚙️ Configurable Parameters

| Constant  | Description                                 |
|-----------|---------------------------------------------|
| `PAUSE`   | Controls speed of animation (lower = faster)|
| `ROWS`    | Contains varying widths to mimic rotation   |

## 💡 Extension Ideas

- Add color coding for base pairs using `colorama`
- Display labels or scrolling sequence data alongside animation
- Turn into an educational module with base pair statistics
- Incorporate mutation or replication simulation
- Convert to GUI using `tkinter` or `pygame`

