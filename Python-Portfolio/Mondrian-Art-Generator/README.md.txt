# 🟥 Mondrian Art Generator — Terminal-Based Abstract Art

A Python program that randomly generates abstract art in the style of Piet Mondrian using terminal graphics. This project uses colored rectangles and bold black lines to create minimalist compositions inspired by the De Stijl movement.

Adapted from *The Big Book of Small Python Projects* by Al Sweigart.

---

## 📌 Project Description

The Mondrian Art Generator creates randomized grid-based artwork using vertical and horizontal lines, filled rectangles, and primary colors. It uses the `bext` module to render colored blocks directly in the terminal. Each composition is unique and generated with a blend of structure and randomness.

---

## 🛠️ Features

- 🎨 Randomized vertical and horizontal line placement  
- 🧱 Intelligent segment deletion to avoid intersections  
- 🟥 Flood-fill coloring of enclosed rectangles  
- 🖼️ Terminal rendering using background colors  
- 🔁 Continuous generation loop with user prompt

---

## 🚀 How to Run

1. Install the `bext` module if not already installed:
   ```bash
   pip install bext
   ```

2. Run the program:
   ```bash
   python mondrian_art_generator.py
   ```

3. Press **Enter** to generate a new artwork or **Ctrl+C** to exit.

---

## 🎨 Color Palette

| Color   | Usage         |
|---------|---------------|
| White   | Background    |
| Black   | Grid lines    |
| Red     | Rectangle fill |
| Yellow  | Rectangle fill |
| Blue    | Rectangle fill |

---

## 🧠 Concepts Demonstrated

- Grid-based canvas modeling with dictionaries  
- Randomized line generation and deletion logic  
- Flood-fill algorithm for coloring enclosed regions  
- Terminal-based rendering using `bext.bg()`  
- Interactive loop with graceful exit handling

---

## 📁 File Structure

```
mondrian_art_generator.py
README.md
```

---

## 📚 Attribution

Original concept by [Al Sweigart](https://nostarch.com/big-book-small-python-projects).  
Documented and adapted by Nathan for educational and portfolio purposes.

---

## 🧪 Try It Yourself

Run the program multiple times to explore the variety of compositions. Each piece is algorithmically generated and visually distinct—just like a digital Mondrian.

