# 🎲 Million Dice Roll Statistics Simulator

A Python simulation that rolls a user-defined number of six-sided dice one million times and records the statistical distribution of the results.

## 📌 Project Overview

This program performs a large-scale simulation of dice rolls to demonstrate probability distribution and randomness. Users specify how many dice to roll per trial, and the program runs one million trials, tracking the frequency and percentage of each possible total.

Inspired by a project from *The Big Book of Small Python Projects* by Al Sweigart.

## 🚀 How It Works

1. **User Input**: Prompts the user to enter the number of six-sided dice to roll.
2. **Simulation**: Rolls the specified number of dice one million times.
3. **Statistics**: Tracks how often each possible total appears.
4. **Output**: Displays a summary of totals, roll counts, and percentages.

## 📊 Sample Output

```
Million Dice Roll Statistics Simulator
By Al Sweigart al@inventwithpython.com

Enter how many six-sided dice you want to roll:
> 2
Simulating 1,000,000 rolls of 2 dice...
TOTAL - ROLLS - PERCENTAGE
  2 - 2771 rolls - 0.3%
  3 - 5543 rolls - 0.6%
  ...
  12 - 27741 rolls - 2.8%
```

## 🧠 Concepts Demonstrated

- Random number generation
- Dictionary-based frequency tracking
- Time-based progress feedback
- Basic probability and statistics

## 🛠️ Requirements

- Python 3.x
- No external libraries required

## 📁 File Structure

```
million_dice_simulator.py
README.md
```

## 📚 Attribution

Original concept by [Al Sweigart](https://nostarch.com/big-book-small-python-projects).  
Modified and documented by Nathan for portfolio enhancement and educational purposes.

## 🧪 Try It Yourself

Run the script and experiment with different numbers of dice to observe how the distribution changes. This is a great way to visualize the central limit theorem in action!

---
