# 🤪 Gullible — A Python Joke Program

Ever wanted to keep a gullible person busy for hours? This tongue-in-cheek script does exactly that — and nothing else. It loops until the player finally says “no,” poking fun at endlessly repeated prompts.

## 🧠 Objective

To demonstrate how minimal logic can be hilariously effective. The joke: the player keeps confirming they want to know how to keep a gullible person busy... which keeps them busy.

## 🎯 What It Does

- Prompts the player with a yes/no question
- Responds to `"yes"` by asking the same question again — endlessly
- Responds to `"no"` by ending the game politely
- Validates input and clarifies when given an invalid response

## 🚀 How to Run

```bash
python gullible.py
```

Respond to the prompt with `Y/N`. See how long you can last before breaking the cycle!

## 🛠️ Learning Highlights

- Uses an infinite `while True` loop
- Demonstrates input handling and basic branching (`if`, `continue`, `break`)
- Practices `.lower()` string normalization for case-insensitive input
- Shows how a few lines of Python can express a full joke

## 🤓 Extension Ideas

- Count and report how many times the player said “yes”
- Randomize the message after each loop to maintain surprise
- Add sound or visual effects for dramatic flair
- Let the user "escape" if they find the hidden exit phrase