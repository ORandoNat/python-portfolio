# 🎲 Lucky Stars

A multiplayer "press-your-luck" dice game where players gather as many stars as they dare—until the skulls take it all away.

Inspired by *Zombie Dice* by Steve Jackson Games  
Adapted from a project in [*The Big Book of Small Python Projects*](https://nostarch.com/big-book-small-python-projects) by Al Sweigart

---

## 📌 Features

- Roll dice to collect ⭐ Stars and avoid 💀 Skulls  
- Decide to roll again or cash out after each turn  
- Dynamic ASCII art for visual dice feedback  
- Multiplayer support with turn rotation  
- Game ends when a player reaches 13 points

---

## 🧠 Game Rules

- Each turn begins with 3 randomly selected dice from the cup (6 Gold, 4 Silver, 3 Bronze)
- Dice faces include:
  - **Star** → earns points
  - **Skull** → risk of losing all current turn points
  - **Question Mark** → neutral, rerolled next round
- Rolling 3 Skulls ends the turn and forfeits all stars earned that round
- A player may end their turn early to lock in their stars
- Once any player reaches **13 points**, all others get one final turn
- The player with the highest score wins

---

## 💻 How to Run

```bash
python lucky_stars.py
```

- You'll be prompted to enter number of players and their names
- Dice rolls will be displayed with ASCII art per turn
- Respond with `Y` or `N` when asked if you'd like to roll again

---

## 🧱 Dice Composition

| Dice Type | Star Faces | Skull Faces | Question Marks |
|-----------|------------|-------------|----------------|
| Gold      | 3          | 1           | 2              |
| Silver    | 2          | 2           | 2              |
| Bronze    | 1          | 3           | 2              |

---

## 🛠️ Technologies Used

- Python (Standard Library)
- `random` module for shuffling and rolling

---

## 📂 File Structure

```
lucky_stars.py         # Main game script
README.md              # Documentation file
```

---

## 🚧 Potential Improvements

- Add sound effects or GUI via `tkinter`
- Include player stats/logs after each game
- Save/load game states for longer sessions
