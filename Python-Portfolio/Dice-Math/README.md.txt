# 🎲 Dice Math — ASCII Addition Game

A fast-paced terminal game where players sum the values shown on randomly placed ASCII dice within a time limit. It blends visual recognition, mental math, and randomness to create a fun flashcard-style challenge.

## 🧩 Game Objective

You have **30 seconds** to solve as many dice math puzzles as possible. For each round, a number of dice appear randomly across the screen. Your task: add up the number of pips and input the correct sum!

- ✅ Gain **4 points** for a correct answer  
- ❌ Lose **1 point** for an incorrect answer

Want a twist? You can even modify it to award points for wrong answers — just flip the `PENALTY` sign!

## 🛠️ Features

- ASCII-rendered dice with randomized faces and positions
- Logic to prevent overlapping dice on a fixed-size canvas
- Time-limited challenge using system clocks
- Scoring system with reward and penalty dynamics
- Modular dice face definitions with pip mapping

## 📦 Technologies Used

- Python 3
- Standard Libraries: `random`, `time`

## 📏 Configurable Constants

| Constant         | Purpose                             |
|------------------|-------------------------------------|
| `QUIZ_DURATION`  | Time limit (seconds)                |
| `MIN_DICE`       | Minimum dice per round              |
| `MAX_DICE`       | Maximum dice per round              |
| `REWARD`         | Points per correct response         |
| `PENALTY`        | Points deducted for wrong answers   |
| `CANVAS_WIDTH`   | Width of terminal canvas            |
| `CANVAS_HEIGHT`  | Height of terminal canvas           |

## 🚀 How to Run

```bash
python dice_math.py
```

Follow the prompts, view the dice, and enter your answer — fast!

## 🎯 Learning Highlights

- Practiced collision detection using bounding boxes
- Designed flexible ASCII-rendered UI using nested loops
- Handled real-time scoring and timed gameplay
- Strengthened randomization logic with multiple die styles
- Explored user input parsing and robust validation

## 💡 Extension Ideas

- Add difficulty scaling (more dice or faster rounds)
- Include sound alerts or countdown timer visuals
- Track high scores across sessions
- Add QA-style unit tests for rendering, overlap, and scoring
- Build GUI using `tkinter` or expand to multiplayer quiz format
