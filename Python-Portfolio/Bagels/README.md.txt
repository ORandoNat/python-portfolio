# 🕵️ Bagels — A Deductive Logic Game

A Python-based number guessing game that challenges players to uncover a secret number using logical deduction and minimal clues. Originally authored by Al Sweigart, this adaptation allows customization of game difficulty through configurable digit length and guess limits.

## 🎯 Objective

Guess the secret number composed of non-repeating digits. Use the clues returned after each guess to refine your strategy.

- **Fermi** — Correct digit in the correct position.
- **Pico** — Correct digit in the wrong position.
- **Bagels** — No digits are correct.

## 🧩 How It Works

- A random secret number is generated using unique digits.
- Players have a limited number of guesses (`MAX_GUESSES`) to identify the number.
- After each guess, clue logic is processed to provide feedback on digit accuracy and position.
- The game continues until the correct number is guessed or guesses run out.

## 🛠️ Features

- Fully interactive terminal-based gameplay loop
- Clear modular functions: `main()`, `getSecretNum()`, `getClues()`
- Adjustable difficulty with `NUM_DIGITS` and `MAX_GUESSES`
- Strong use of control flow, user input validation, and list operations

## 🚀 Technologies Used

- Python 3
- `random` module for shuffling digits

## 🧠 Learning Highlights

- Applied game logic and conditional control structures
- Practiced modular design and function abstraction
- Strengthened skills in validating input and generating dynamic feedback
- Emphasized readability and user experience in terminal apps

## 📚 Source Inspiration

- Based on Al Sweigart’s project from *Invent Your Own Computer Games with Python*
- [Original source and book reference](https://nostarch.com/inventwithpython)

## 📦 How to Run

```bash
python bagels.py
```

## 🔄 Customization Ideas

- Expand to higher-digit games for increased difficulty
- Add a graphical interface using Tkinter or PyGame
- Introduce score tracking or time-based challenges
