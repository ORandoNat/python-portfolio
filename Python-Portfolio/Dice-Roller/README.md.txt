# 🎲 Dice Roller — D&D Style Simulator

A command-line dice roller that interprets classic Dungeons & Dragons (DnD) notation. Supports complex input like `2d10+5` or `3d6-2` to simulate a variety of dice types and modifiers. Great for tabletop gamers, developers testing randomness, or anyone who appreciates structured CLI input parsing.

## 🔠 Notation Supported

- `NdS+M` where:
  - `N` = number of dice
  - `S` = number of sides on each die
  - `M` = optional modifier (positive or negative)

### 🧾 Examples

| Input     | Meaning                              |
|-----------|--------------------------------------|
| `3d6`     | Roll three six-sided dice            |
| `2d10+4`  | Roll two ten-sided dice + 4          |
| `1d20-1`  | Roll one twenty-sided die − 1        |
| `QUIT`    | Exit the simulation gracefully       |

## 🛠️ Technologies Used

- Python 3
- Libraries: `random`, `sys`

## 💻 How to Run

```bash
python dice_roller.py
```

Follow the prompts, enter your roll, and see the results instantly.

## 🚀 Features

- Parses input strings with dice and modifiers
- Validates notation and returns user-friendly errors
- Randomly simulates dice rolls per spec
- Outputs individual roll results and total
- Supports dynamic modifier parsing (`+` or `−`)
- Quits cleanly on `QUIT`

## 🧠 Learning Highlights

- Built robust input parsing logic with string slicing
- Used random number generation within specified bounds
- Practiced exception handling and user input validation
- Provided clear formatting for CLI feedback

## 🔁 Future Enhancements

- Add support for roll repetitions (e.g. `5x2d6`)
- Integrate probability tracking or roll history
- Extend with `adv`/`dis` mechanics for DnD rules
- Build a GUI interface or web app using Flask
- Write unit tests to validate parsing and output

