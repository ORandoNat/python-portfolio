# 🔓 Caesar Cipher Hacker — Brute Force Decryption Tool

A simple Python script designed to brute-force decrypt messages encoded with the classic Caesar Cipher. This project systematically tests all possible shift key values to unveil the most readable result, offering an educational look at basic cipher vulnerabilities.

## 🧠 Project Objective

Demonstrate how simple encryption methods like Caesar Cipher can be broken easily using brute-force attacks — reinforcing the importance of stronger encryption protocols in real-world scenarios.

## ⚙️ How It Works

- Accepts an encrypted message from the user
- Iterates over all possible Caesar cipher keys (0 to 25)
- Decrypts the message for each key
- Displays all potential results for manual inspection

## 🛠️ Features

- Works with uppercase A-Z (can be extended to include punctuation and digits)
- Exhaustive brute-force attempt with wrap-around logic
- Highlights how insecure fixed-shift ciphers can be

## 🚀 Technologies Used

- Python 3
- Simple string manipulation and control flow

## 🧪 Learning Highlights

- Strengthened understanding of Caesar Cipher structure
- Practiced brute-force decryption logic
- Implemented wrap-around arithmetic with modular bounds
- Explored cryptographic principles and human-in-the-loop analysis

## 📦 How to Run

```bash
python caesar_cipher_hacker.py
```

Enter the encrypted message when prompted. The script will display all 26 key attempts.

## 📚 References

- Based on Al Sweigart’s version from *The Big Book of Small Python Projects*
- [Caesar Cipher on Wikipedia](https://en.wikipedia.org/wiki/Caesar_cipher#Breaking_the_cipher)

## 🔄 Customization Ideas

- Automatically highlight most English-readable results using frequency analysis
- Add support for extended symbols: lowercase, numbers, and punctuation
- Integrate clipboard or file input/output
- Wrap logic into a function and write unit tests for QA practice
- Add command-line arguments for scripting and automation
