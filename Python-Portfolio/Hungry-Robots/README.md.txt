# 🤖 Hungry Robots

Escape the robotic mayhem in this strategic survival game! Inspired by classic logic games, *Hungry Robots* challenges you to outwit relentless, pathfinding bots in a grid-based maze — armed only with quick thinking and a limited-use teleporter.

![Screenshot Placeholder](#) <!-- Add a gameplay screenshot here if you’d like -->

## 📦 Features

- Grid-based maze packed with randomized walls and obstacles
- Intelligent robot movement that dynamically tracks the player
- Dead robots and crash sites add strategic depth
- Personal teleportation device for emergency escapes
- Corner-slipping wall mechanic for added challenge
- Modular constants for easy game customization

## 🧠 How It Works

Robots are programmed to blindly chase the player in straight lines, regardless of obstacles. You can escape by:

- Tricking them into crashing into each other or dead robots
- Using teleports wisely
- Navigating around walls and avoiding being cornered

## 🕹️ Controls

```
Q W E      Move diagonally or straight
A S D      S = Stay in place
Z X C      
T          Teleport (limited uses)
QUIT       Exit the game
```

## ⚙️ Configuration Options

Tweak constants at the top of the script to adjust gameplay:

| Constant          | Description                         |
|-------------------|-------------------------------------|
| `WIDTH`, `HEIGHT` | Size of the board                   |
| `NUM_ROBOTS`      | Total living robots                 |
| `NUM_TELEPORTS`   | Teleports available to the player   |
| `NUM_DEAD_ROBOTS` | Starting dead robot count           |
| `NUM_WALLS`       | Randomly placed walls on the board  |

## 🚀 Getting Started

```bash
python hungry_robots.py
```

Requires Python 3. No external libraries needed.

## 🧪 Test Ideas

- Modify robot count to stress test collision logic
- Set `NUM_TELEPORTS` to 0 for hardcore mode
- Increase walls for intricate mazes

## 📚 Attribution

Based on *Hungry Robots* by [Al Sweigart](https://nostarch.com/big-book-small-python-projects)  
📧 `al@inventwithpython.com`
