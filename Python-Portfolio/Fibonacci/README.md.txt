# 🧮 Fibonacci Sequence Calculator — Terminal Edition

A command-line utility that calculates the Nth number in the Fibonacci sequence. This elegantly structured script outputs the full sequence up to the requested position and gracefully handles edge cases. Simple in concept, but foundational in computer science and mathematics.

## 🔢 What is Fibonacci?

The Fibonacci sequence starts with:
```
0, 1
```
Each subsequent number is the **sum of the previous two**:
```
0, 1, 1, 2, 3, 5, 8, 13, 21, ...
```
Fibonacci numbers appear throughout nature, cryptography, and algorithmic design — this script makes them come alive line by line.

## 🛠️ Features

- Accepts any valid integer `n > 0` and calculates the nth Fibonacci number
- Displays the entire sequence up to `n`
- Special case handling for `n = 1` and `n = 2`
- Warns about large inputs for performance awareness
- Graceful exit with `QUIT`
- Uses a loop-based iterative approach (no recursion)

## 📦 Technologies Used

- Python 3
- Standard libraries: `sys`

## 🚀 How to Run

```bash
python fibonacci_sequence.py
```

Follow the prompt and enter the desired `n` value, or type `QUIT` to exit.

## 🧠 Learning Highlights

- Explored loop-based calculation with dynamic tracking of prior values
- Implemented user input validation and conditional branching
- Practiced formatted string output and comma-separated printing
- Used control flow structures to manage program continuity
- Demonstrated algorithmic efficiency with no recursion

## 🔧 Customization Ideas

- Switch to recursive implementation or memoization for practice
- Create a generator that yields infinite Fibonacci numbers
- Write a test suite using `unittest` or `pytest` to validate outputs
- Display timing benchmarks for large input values
- Export results to CSV or visualize using `matplotlib`

