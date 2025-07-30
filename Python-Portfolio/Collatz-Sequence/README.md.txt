# 🔁 Collatz Sequence — Explore the 3n + 1 Conjecture

A Python implementation of the famous Collatz Conjecture, a mathematical sequence that applies a simple set of rules to any positive integer. The program calculates and prints the resulting Collatz sequence in real-time, showcasing how even basic operations can lead to surprising behavior.

## 📘 What Is the Collatz Sequence?

Starting from any number `n`:
1. If `n` is even → divide it by 2
2. If `n` is odd → multiply by 3 and add 1
3. Repeat until `n` becomes 1

Though simple, it’s unproven whether all positive integers eventually reach 1 — making this a fun and puzzling topic in mathematics.

- [Wikipedia: Collatz Conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture)

## 🛠️ Features

- Interactive input validation
- Real-time sequence printing with timed spacing
- Handles any positive integer
- Educational demonstration of looping logic and conditional arithmetic

## 🚀 Technologies Used

- Python 3
- Standard libraries: `sys`, `time`

## 🧠 Learning Highlights

- Applied loop and conditionals to a real-world math problem
- Practiced input handling and graceful exit strategies
- Used `time.sleep()` for smooth output pacing
- Reinforced integer division and modulus operations
- Explored recursive-like behavior through iteration

## 📦 How to Run

```bash
python collatz_sequence.py
```

Follow the prompt to enter a positive integer. The sequence will animate until it reaches 1.

## 🔄 Customization Ideas

- Visualize the sequence with `matplotlib`
- Count and report number of steps to reach 1
- Animate a graph of sequence values over time
- Add batch mode to test multiple starting values
- Integrate unit tests to support QA-style function validation
