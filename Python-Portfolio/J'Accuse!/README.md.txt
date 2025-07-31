# J'ACCUSE! - A Mystery Game of Intrigue and a Missing Cat 🕵️🐱

A comical deduction-style mystery adventure written in Python, inspired by Homestar Runner's "Where's an Egg?" and created by Al Sweigart. You play as Mathilde Camus, world-famous detective, trying to solve the case of Zophie the missing cat. Each suspect either always lies or always tells the truth. Your mission: uncover clues, spot inconsistencies, and solve the feline caper before time runs out.

🔗 Original Flash game inspiration: [Where's an Egg?](https://homestarrunner.com/videlectrix/wheresanegg.html)  
📚 Source: [Big Book of Small Python Projects](https://nostarch.com/big-book-small-python-projects)

### 🎮 Gameplay Features
- ⏱️ Timed mystery — solve in under 5 minutes
- 🔍 Unique suspects, locations, and items randomized per game
- 🗣️ Dynamic clue system: truthful and deceptive interviews
- 🚖 TAXI hub navigation for clue-chasing
- 🧠 Logical deduction mechanics for tracking relationships
- 📦 Replayable with reshuffled clues and suspects


### 🧠 How It Works
- Nine suspects, each placed at a unique location with a unique item
- Suspects are randomly assigned as either liars or truth-tellers
- Clue dictionaries built for both truthful and false information
- Game loop allows player to travel, interrogate, and accuse
- Incorrect accusations limit further interactions — choose wisely!

### 🛠️ Technologies & Design
- Python 3 standard library (time, random, sys)
- Modular constants for suspects, places, and items
- Data structures for clue logic and game state
- Minimalist terminal interface
- Inspired by classic text adventure logic puzzles

### 💡 Learning & Educational Value
This project demonstrates:
- Use of randomness for dynamic game flow
- Dictionary-based clue logic
- Input validation and loop handling
- Game state management (visited places, known clues)
- Debug structures for development insights

### 📈 Potential Enhancements
- 🗂️ GUI implementation (e.g. with tkinter or PyQt)
- 🧵 Save/load functionality for mid-game progress
- 🧩 Achievement or scoring system based on time/accuracy
- 🎨 ASCII art for suspects or locations
