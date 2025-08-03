# 🧠 Leetspeak Translator

A playful Python utility that converts regular English text into randomized **l33t5p34]<**, the stylized "leet" language used in internet culture. This script makes your messages look tech-savvy or cryptic—perfect for fun projects or encoding easter eggs.

## 📌 Project Details

- **Author**: Original concept by Al Sweigart [al@inventwithpython.com]
- **Source**: [Big Book of Small Python Projects](https://nostarch.com/big-book-small-python-projects)
- **Tags**: `tiny`, `beginner`, `word`, `string manipulation`, `text encoding`
- **License**: Refer to original author's repository or publication for licensing.

## 🚀 Features

- Converts English text to randomized leetspeak.
- Supports multi-symbol mapping for letters (e.g., `a → 4`, `@`, `/-\`).
- Clipboard copy functionality via `pyperclip` (optional).
- ~70% chance of converting eligible characters to add unpredictability.
- Lightweight and beginner-friendly—perfect for experimenting with string operations and randomness.

## 🔧 How It Works

The program defines a dictionary mapping English characters to lists of possible leetspeak substitutions. It iterates through the input message and, with a random chance, replaces eligible characters with a leetspeak variant. This randomness adds uniqueness to each output.

Example:

```text
Input:  Hello world!
Output: ]-[3||0 \\/0|)|
```

## 📦 Requirements

- Python 3.x
- Optional: `pyperclip` module for automatic clipboard copying


pip install pyperclip

## ▶️ Usage

Run the script from your terminal or IDE:

python leetspeak.py

You'll be prompted to enter a message. The translated leetspeak output will be displayed, and if `pyperclip` is installed, it'll be copied to your clipboard for easy sharing.

## 📁 File Structure

```
leetspeak.py    # Main executable script
README.md       # Project documentation
```

## 💡 Opportunities for Extension

- Add a GUI using `tkinter` for interactive leetspeak generation.
- Include custom character mappings or themes (e.g., gamer mode, hacker mode).
- Save and load translation presets.

## 🙌 Acknowledgements

Thanks to [Al Sweigart](https://inventwithpython.com) for the original concept and code inspiration.
