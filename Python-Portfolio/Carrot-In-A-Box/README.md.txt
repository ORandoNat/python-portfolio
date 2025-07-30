# 🥕 Carrot in a Box — Terminal Bluffing Game for Two Players

A hilarious Python-based bluffing game inspired by the British TV show *8 Out of 10 Cats*. Two players face off with mysterious boxes, one containing a carrot. The first player sees inside their box and must bluff (or tell the truth) to outwit their opponent. The second player must decide whether to swap — and the carrot determines the winner.

## 🎯 Gameplay Overview

- Two ASCII-art boxes are displayed: RED and GOLD.
- One randomly contains the carrot.
- Player 1 peeks inside their box and announces if the carrot is present (truthfully or not).
- Player 2 decides whether to swap boxes based on player 1's claim.
- The winner is revealed dramatically based on where the carrot actually ended up.

## 🛠️ Features

- Two-player interactive terminal experience
- Color-coded box ASCII art with visual carrot/no-carrot reveal
- Randomized carrot placement logic
- Dramatic screen clearing for suspense and immersion
- Simple and silly bluff-based decision-making

## 🚀 Technologies Used

- Python 3
- Standard library: `random`, `input`, and string formatting

## 🧠 Learning Highlights

- Practiced user input handling and validation
- Reinforced conditional logic and game flow control
- Generated ASCII visuals using multi-line strings and formatted layouts
- Introduced randomization to simulate unpredictability in games
- Used variables to track game state and swap logic

## 📦 How to Run

```bash
python carrot_in_a_box.py
```

Make sure two players are available and ready to play on the same terminal.

## 📚 Source Inspiration

- Based on Al Sweigart’s version from *The Big Book of Small Python Projects*
- Inspired by the bluffing segment on *8 Out of 10 Cats* [Wikipedia](https://en.wikipedia.org/wiki/8_Out_of_10_Cats)

## 🔄 Customization Ideas

- Add color with `colorama` for vivid red/gold box representation
- Implement scores across multiple rounds
- Include AI bluffing logic for solo play
- Log bluff vs truth results to analyze strategies
- Add sound effects or delays for comedic timing
