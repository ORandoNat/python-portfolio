# 🧩 Maze Runner 2D — Terminal-Based Maze Navigation Game

Navigate a procedurally generated maze in this classic terminal-based puzzle game. Load a maze file, find your starting point, and use directional input to reach the exit. Built for exploration, logic, and a satisfying escape.

Adapted from [The Big Book of Small Python Projects](https://nostarch.com/big-book-small-python-projects) by Al Sweigart  
Maze files generated using `mazemakerrec.py`

---

## 📌 Features

- Loads maze files from `.txt` format  
- ASCII-rendered maze with walls, paths, start, and exit  
- Player movement with auto-run until branch or wall  
- Exit detection and win condition  
- File listing and validation for user-friendly setup

---

## 🧠 Game Rules

- You begin at the `S` (Start) tile and must reach the `E` (Exit)  
- Use `W`, `A`, `S`, `D` to move up, left, down, and right  
- Movement continues until a wall or branch is encountered  
- Maze files must contain only valid characters: `#`, ` `, `S`, `E`  
- Press `QUIT` to exit the game at any time

---

## 💻 How to Run

```bash
python maze_runner_2d.py
```

- When prompted, enter the filename of a maze (e.g., `maze1.txt`)  
- Use `LIST` to view available maze files in the current directory  
- Navigate using keyboard input until you reach the exit

---

## 🧱 Maze File Format

Maze files are plain text and must follow these rules:

| Symbol | Meaning         |
|--------|-----------------|
| `#`    | Wall            |
| ` `    | Empty space     |
| `S`    | Start position  |
| `E`    | Exit position   |

Each maze must contain exactly one `S` and one `E`.

---

## 🧠 Learning Highlights

- File I/O for loading and validating maze data  
- Dictionary-based grid representation  
- Real-time rendering with ASCII characters  
- Movement logic with auto-run and branching detection  
- Input handling and game loop control

---

## 🛠️ Technologies Used

- Python (Standard Library)
  - `os` for file listing and path validation  
  - `sys` for program control  
  - No external dependencies required

---

## 🚧 Possible Extensions

- Add timer or move counter for performance tracking  
- Implement fog-of-war or limited visibility  
- Create a maze editor or visualizer  
- Add sound effects or animations with `curses` or `pygame`
