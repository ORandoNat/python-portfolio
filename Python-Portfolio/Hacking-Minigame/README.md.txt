# 💻 Hacking Minigame — Inspired by Fallout 3

A terminal-based word-guessing puzzle where the player searches a simulated computer memory dump to crack the password. Each guess reveals how many letters match the correct password in the same position — narrowing your chances over four tries.

## 🧠 Objective

Find the secret seven-letter password by deducing patterns and position-based matches. Words are embedded within lines of randomized "garbage" text, mimicking a stylized memory dump.

## 🖥️ Gameplay Features

- Random selection of 12 candidate seven-letter words
- Cosmetic “computer memory” dump generated using random symbols
- Players receive feedback with letter-position match counts
- Input validation ensures guesses must be in the candidate list
- Game ends on correct guess or after four failed attempts
- KeyboardInterrupt gracefully handled

## 🚀 How to Play

```bash
python hacking_minigame.py
```

You'll need a file named `sevenletterwords.txt` containing valid words.  
On each turn, type one of the displayed words to guess the password.

## 🛠️ Learning Highlights

- Word filtering via character-position comparison
- Cosmetic rendering of memory with randomized filler characters
- Embedded word injection using slicing and index logic
- List manipulation, randomness, and input sanitization
- Terminal interaction patterns with minimal dependencies

## 🧪 Extension Ideas

- Add difficulty modes with word length or guess limits
- Create a word list file dynamically if not present
- Use color output to highlight matches (e.g., using `colorama`)
- Track guesses and stats across sessions
- Convert to GUI using `tkinter` or web app with `Flask`

## 📁 Required Resource

Make sure `sevenletterwords.txt` is in the same directory.  
Each word should be one line, formatted in uppercase or lowercase — no whitespace.

