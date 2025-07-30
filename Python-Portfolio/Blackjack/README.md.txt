# 🃏 Blackjack — A Classic Card Game in Python

A terminal-based Python implementation of Blackjack (also known as 21) that simulates a full round of gameplay between a player and a dealer. This version features betting, doubling down, hand evaluation, and ASCII-rendered cards — without splitting or insurance.

## 🎯 Objective

Try to get as close to 21 as possible without going over. Beat the dealer's hand to win your bet. Face cards are worth 10 points, Aces are worth 1 or 11 (whichever is more favorable), and all other cards retain their face value.

## 🛠️ Features

- Interactive gameplay with betting and decision-making
- Full deck generation and random shuffling
- Smart Ace value calculation (1 or 11)
- Double-down option on the initial deal
- Dealer plays by standard rules (hits until 17)
- ASCII representation of cards for visual feedback
- Graceful handling of invalid input and exit conditions

## 🚀 Technologies Used

- Python 3
- Standard libraries: `random`, `sys`

## 🧠 Learning Highlights

- Built custom deck and hand evaluation logic
- Practiced modular function design (`getBet()`, `getDeck()`, `getMove()`, `getHandValue()`, etc.)
- Reinforced use of tuples, lists, and control structures
- Demonstrated robust input handling and gameplay loops
- ASCII art rendering and formatted output for user clarity

## 📚 Source Inspiration

- Based on Al Sweigart’s project from *The Big Book of Small Python Projects*
- [Blackjack Wikipedia](https://en.wikipedia.org/wiki/Blackjack)

## 📦 How to Run

```bash
python blackjack.py
```

Follow the prompts to place your bets, take actions, and try your luck against the dealer.

## 🔄 Customization Ideas

- Add support for splitting pairs or insurance bets
- Track session stats: wins, losses, money earned/lost
- Integrate testing hooks for evaluating core game logic (QA-ready modularity)
- Create a GUI version with Tkinter or web-based UI using Flask
- Introduce difficulty settings (aggressive dealer, limited bankroll, etc.)
