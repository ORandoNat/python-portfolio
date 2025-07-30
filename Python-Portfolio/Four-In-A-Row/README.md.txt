# 🎯 Four in a Row — A Connect Four Style Game in Python

A two-player terminal game based on the classic Connect Four concept. Players take turns dropping tiles into columns, aiming to form a horizontal, vertical, or diagonal line of four. Simple inputs, clean ASCII grid, and satisfying logic make it a fun and educational challenge.

## 🧠 Objective

Drop your tiles strategically to create a sequence of four in a row — while blocking your opponent from doing the same. The first player to connect four wins!

## 🛠️ Features

- Supports two-player turn-based input
- Board represented with a dictionary of tile positions
- Automatically detects win states in four directions:
  - Horizontal
  - Vertical
  - Diagonal (↘ and ↙)
- Detects tie conditions when board is full
- Graceful exit with `QUIT`
- Simple 7x6 grid and easy-to-read visuals

## 🚀 How to Run

```bash
python four_in_a_row.py
```

Enter column numbers (1–7) when prompted. Type `QUIT` to exit the game.

## 🎮 Symbols Used

| Symbol | Meaning       |
|--------|---------------|
| `X`    | Player X tile |
| `O`    | Player O tile |
| `.`    | Empty space   |

## 📏 Configurable Constants

You can tweak these settings to modify the game’s dimensions:

| Constant         | Description                      |
|------------------|----------------------------------|
| `BOARD_WIDTH`    | Number of columns (default: 7)   |
| `BOARD_HEIGHT`   | Number of rows (default: 6)      |
| `COLUMN_LABELS`  | Column header labels             |

## 🧠 Learning Highlights

- Used dictionary-based grid modeling (`(col, row)` keys)
- Applied nested loops for win detection and game progression
- Designed functional structure: input → validation → board update → check win/tie → switch turn
- Practiced string formatting and alignment for board display
- Handled real-time input edge cases (full column, invalid entry, exit trigger)

## 🧪 Extension Ideas

- Add AI player with simple strategy or random moves
- Convert game to GUI using `tkinter` or web-based with `Flask`
- Add score tracking for best-of-N matchups
- Integrate sound effects or animation
- Write unit tests for board creation, input validation, and win checks
