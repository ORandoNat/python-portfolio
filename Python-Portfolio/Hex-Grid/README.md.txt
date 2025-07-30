# 🔷 Hex Grid — ASCII Tessellation in Python

This tiny artistic program renders a tessellated grid of hexagons using simple print statements and loop logic. Ideal for exploring patterns, repetition, and creative character-based visual design.

## 🧠 Objective

Generate a seamless tiling of hexagons across the terminal screen using two-character-wide lines. Great for learning how nested loops produce structured output.

## 🛠️ Features

- Configurable grid dimensions via constants:
  - Horizontal repeats (`X_REPEAT`)
  - Vertical repeats (`Y_REPEAT`)
- Hexagons drawn using `/ \_` and `\_/` characters
- Clean, consistent ASCII tessellation
- Excellent for artistic experiments or customizing as game map backgrounds

## 🚀 How to Run

```bash
python hex_grid.py
```

Customize the `X_REPEAT` and `Y_REPEAT` constants to control grid size.

## ✏️ Learning Highlights

- Practiced nested `for` loops to handle row and column repetition
- Explored ASCII character alignment using string literals
- Learned how `print(..., end='')` avoids unwanted line breaks
- Reinforced how control over flow and indentation impacts visual output

## 🎨 Extension Ideas

- Add staggered hex alignment for a true honeycomb shape
- Color the grid using `colorama`
- Animate the pattern dynamically line-by-line
- Use hexes as placeholders for game cells, map zones, or pixel art
- Convert to function-based design for reusable grid generators