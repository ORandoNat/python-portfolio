# 🎂 Birthday Paradox Simulation

A Python-based Monte Carlo simulation that explores the famous "Birthday Paradox": how likely it is for two people in a group to share the same birthday. This project demonstrates probabilistic reasoning using simulated data and basic statistical methods.

## 📚 Concept Overview

Despite seeming counterintuitive, the probability that two people share a birthday in a small group is surprisingly high. For example, in a room of just 23 people, there's over a 50% chance of a shared birthday.

- Learn more: [Wikipedia - Birthday Problem](https://en.wikipedia.org/wiki/Birthday_problem)

## 🧪 How It Works

1. Prompt the user for a number of people (up to 100)
2. Randomly generate birthdays for that number of people
3. Check for duplicates (matching birthdays)
4. Run 100,000 simulations to estimate probability of matches
5. Report frequency and percentage of simulations with shared birthdays

## 🛠️ Features

- Interactive user input with validation
- Uses Python’s `datetime` module to generate and compare dates
- Implements set-based uniqueness checking and pairwise comparison
- Performs 100,000 simulations to approximate real-world probabilities

## 🚀 Technologies Used

- Python 3
- `datetime` and `random` modules
- Basic statistical reasoning and simulations

## 🧠 Learning Highlights

- Practiced Monte Carlo simulation techniques
- Worked with Python’s `datetime` and `timedelta` objects
- Reinforced understanding of set operations and efficient comparison logic
- Strengthened control flow with loops, conditional logic, and performance tracking

## 📦 How to Run

```bash
python birthday_paradox.py
```

Follow the prompts to select your group size and observe the results of the simulation.

## 🔄 Customization Ideas

- Visualize results with matplotlib or seaborn
- Add plotting for distribution of probabilities across different group sizes
- Introduce GUI elements with Tkinter for more engaging interaction
- Apply unit testing to functions for QA-readiness
- Track average simulation time and performance metrics
