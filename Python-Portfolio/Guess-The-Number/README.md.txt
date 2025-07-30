# 🎲 Guess the Number — Terminal Game in Python

A beginner-friendly guessing game where the player tries to identify a randomly selected secret number between 1 and 100 in just 10 attempts. Designed with clear prompts and feedback hints to guide players toward the correct guess.

## 🧠 Objective

Guess the secret number using logic and deduction. After each guess, the game offers hints — telling you whether your guess was too low or too high. The goal: find the number in 10 tries or less.

## ⚙️ Features

- Generates a random number from 1 to 100
- Accepts and validates user input
- Offers high/low hints after each guess
- Tracks remaining guesses
- Ends with a success or reveal message
- Gracefully handles invalid input and exits

## 🚀 How to Play

```bash
python guess_the_number.py
```

- Enter a number between 1 and 100 when prompted.
- After each guess, you'll receive feedback to guide your next move.
- You've got 10 chances — make them count!

## 🛠️ Learning Highlights

- Introduced `random.randint()` for number generation
- Used a loop with controlled iteration for guess attempts
- Practiced `input()` handling and string validation
- Implemented input checks with `.isdecimal()` to avoid errors
- Reinforced control flow with conditionals (`if`, `break`, etc.)
- Explored basic terminal user interactions

## 💡 Extension Ideas

- Add difficulty modes (easy: 15 guesses, hard: 5 guesses)
- Keep score across multiple rounds
- Add GUI with `tkinter` or command-line colors using `colorama`
- Include a leaderboard using file I/O
- Write tests to validate `askForGuess()` behavior and edge cases
