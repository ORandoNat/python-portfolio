# ⚙️ Large Product Calculator — Benchmarking Python Performance

A compact Python script that calculates the product of all integers from 1 to 99,999 and measures how long the computation takes. This micro-project demonstrates how Python handles large integer arithmetic and can be used as a benchmarking tool for processor performance or interpreter behavior.

## 🧮 Project Overview

- Computes the factorial-like product from 1 to 99,999
- Converts the result to a string to count the number of digits
- Measures computation time using `time` module

## 🛠️ Features

- Efficient computation using iterative multiplication
- Performance timing with `time.time()`
- Simple yet impressive handling of very large numbers
- Educational insight into Python’s arbitrary-precision integer support

## 🚀 Technologies Used

- Python 3
- `time` module for runtime benchmarking

## 🧠 Learning Highlights

- Practiced basic performance profiling
- Explored Python’s handling of extremely large integers
- Reinforced iterative processing and benchmarking logic
- Laid groundwork for comparing algorithmic approaches (e.g. recursive factorial vs iterative product)

## 📦 How to Run

```bash
python large_product.py
```

The script will output:
- Number of digits in the computed product
- Time taken to calculate the product

## 🔄 Customization Ideas

- Replace loop with `math.factorial()` for performance comparison
- Store results and timing data for plotting performance graphs
- Run on different systems/interpreters (CPython vs PyPy) for benchmarking
- Add logging and multi-run average timing functionality
