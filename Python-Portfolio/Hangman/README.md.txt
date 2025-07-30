# 🪓 Hangman — Classic Word Guessing Game in Python

Guess the secret word one letter at a time before the full hangman is drawn! This terminal game recreates the iconic pen-and-paper experience with ASCII art and real-time letter validation.

## 🧠 Objective

Prevent the hangman from being fully drawn by correctly guessing letters in a mystery word. If you guess all the letters before exhausting your chances, you win!

## 🛠️ Features

- Visual ASCII gallows progression on incorrect guesses
- Word category: **Animals** (easily customizable)
- Handles repeated letters and invalid inputs gracefully
- Dynamic display of blanks and revealed letters
- Tracks both correct and missed guesses
- Offers win/lose messages with the full word reveal

## 🚀 How to Run

```bash
python hangman.py
```

Guess a letter when prompted — uppercase/lowercase both work. Press `Ctrl+C` to exit at any time.

## 🎮 Symbols Used

| Symbol | Meaning                      |
|--------|------------------------------|
| `_`    | Hidden letter in the word    |
| `O`    | Head of the hangman          |
| `/|\`  | Arms and torso               |
| `/ \`  | Legs                         |

## 🎨 ASCII Art Progression

Each incorrect guess builds the hangman step-by-step.  
You get 6 chances before the full figure is completed.

## ✏️ Learning Highlights

- Designed modular functions for input and board rendering
- Used `.split()` and `.upper()` for clean string handling
- Implemented list and loop logic to update display and track guesses
- Practiced validation techniques for user input

## 💡 Extension Ideas

- Add multiple categories or difficulty modes
- Support full-word guesses in addition to letters
- Include sounds or colors using `colorama`
- Track win/loss stats or rounds
- Turn it into a GUI with `tkinter`

## 🔧 Customization Tips

- Change the `CATEGORY` and `WORDS` list to fit your theme (e.g., foods, tech, cities)
- Modify `HANGMAN_PICS` to create different visuals — gallows, guillotine, robot, etc.

