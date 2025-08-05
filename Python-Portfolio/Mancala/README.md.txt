# 🏺 Mancala — A Two-Player Seed-Sowing Strategy Game

A terminal-based implementation of the ancient board game **Mancala**, designed for two players. Sow seeds, claim territory, and outwit your opponent by strategically navigating the board and timing your final moves. Built entirely in Python, this game reflects elegant turn-based logic and rich historical gameplay.

Adapted from [The Big Book of Small Python Projects](https://nostarch.com/big-book-small-python-projects) by Al Sweigart  
Game rules inspired by traditional Mancala variants — see [Wikipedia](https://en.wikipedia.org/wiki/Mancala)

---

## 📌 Features

- ASCII-rendered game board with real-time seed tracking  
- Seed sowing with counter-clockwise pit progression  
- Capture mechanics for landing in empty pits  
- Auto-handling of bonus turns when ending in your store  
- Game ends when one side is empty — remaining seeds claimed by opponent  
- Win detection with visual announcement

---

## 🧠 Game Rules Summary

- Players take turns selecting pits on their side to distribute seeds  
- Seeds are sown one-by-one into consecutive pits (skipping opponent's store)  
- If the last seed lands in your store → you get another turn  
- If the last seed lands in one of your empty pits → you capture from the opposite pit  
- Game ends when all six pits of one player are empty  
- The other player captures remaining seeds and the winner is declared based on store totals

---

## 💻 How to Run

```bash
python mancala.py
```

- Player 1 controls pits `A`–`F` and Store `1`  
- Player 2 controls pits `G`–`L` and Store `2`  
- Enter the letter corresponding to the pit you want to play from  
- Type `QUIT` anytime to end the game

---

## 🎮 Visual Board Layout

```
+------+------+--<<<<<-Player 2----+------+------+------+  
2      |G     |H     |I     |J     |K     |L     |      1  
       |     |     |     |     |     |     |  
T  00  +------+------+------+------+------+------+  00  T  
O      |A     |B     |C     |D     |E     |F     |      O  
       |     |     |     |     |     |     |  
+------+------+------+-Player 1->>>>>-----+------+------+
```

*Numbers represent the count of seeds in each pit/store.*

---

## 🧠 Learning Highlights

- Dictionary-based board state and pit relationships  
- Circular logic with wrap-around pit transitions  
- Turn validation, win conditions, and move legality checks  
- Clean modular functions with single responsibility principles  
- Interactive ASCII game rendering without external libraries

---

## 🛠️ Technologies Used

- Python (Standard Library)
  - `sys` for program flow control  
  - No external dependencies required

---

## 🪴 Extension Ideas

- Add AI opponent with basic strategy  
- Convert to GUI with mouse interaction using `tkinter`  
- Allow alternate seed counts and pit setups for custom play  
- Implement undo functionality or move history  
- Track game statistics over multiple matches