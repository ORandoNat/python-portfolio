# 🔢 Sevseg — Seven-Segment Display Module in Python

A lightweight utility to render digits as seven-segment display ASCII art. Inspired by digital clocks and calculators, this module provides clean string output of numbers using labeled segments A–G.

## 📟 What It Does

- Converts any number (int or float) into three-line ASCII representation
- Supports decimal points and negative signs
- Useful for countdown timers, clocks, and console dashboards
- Includes optional zero-padding for consistent width formatting

## 🚀 Quick Start

```python
import sevseg

# Render "42" with leading zeros for 3 digits
print(sevseg.getSevSegStr(42, 3))
```

Output:
```
 __        __ 
|  | |__|  __|
|__|    | |__ 
```

## 🔧 Function Reference

### `getSevSegStr(number, minWidth=0)`

| Parameter   | Description                              |
|-------------|------------------------------------------|
| `number`    | Integer or string to display             |
| `minWidth`  | Pads the output with zeros if necessary  |
| Returns     | A string containing 3 rows of ASCII digits|

## ✏️ Learning Highlights

- Character-by-character parsing with conditional formatting
- Zero-padding using `str.zfill()`
- Segment-based visual design using labeled regions (`A` to `G`)
- Modular function-based implementation for easy integration

## 🎯 Extension Ideas

- Add support for alphabet letters (limited segment accuracy)
- Create blinking effects using terminal animation
- Extend into graphical segments using `tkinter` or `pygame`
- Integrate into time-based projects (countdown, stopwatch, clock)
