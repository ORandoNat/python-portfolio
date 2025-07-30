# 🛡️ Caesar Cipher — Classic Encryption Tool

A beginner-friendly implementation of the Caesar Cipher in Python. This shift-based encryption technique replaces each letter with another a fixed number of positions away in the alphabet. Originally used by Julius Caesar for military communications, it's now a popular teaching tool for understanding cryptographic logic.

## 🔐 Project Overview

Users can choose to encrypt or decrypt messages by providing a shift key. The script supports all uppercase English letters and can be extended to include numbers or punctuation.

- **Encryption**: Shifts each letter forward by the key value.
- **Decryption**: Shifts each letter backward by the key value.
- **Clipboard support**: Automatically copies result if `pyperclip` is installed.

## 🛠️ Features

- Supports both encryption and decryption modes
- Wrap-around logic for alphabet rotation
- Interactive prompt for key and message
- Graceful fallback if clipboard module is unavailable
- Easily expandable to support additional symbols

## 🚀 Technologies Used

- Python 3
- Standard libraries: `sys`
- Optional: `pyperclip` (for clipboard functionality)

## 🧠 Learning Highlights

- Practiced string indexing and character manipulation
- Implemented modulo-style wrap-around logic
- Strengthened interactive command-line design
- Used conditional handling for optional modules

## 📦 How to Run

```bash
python caesar_cipher.py
```

Follow the prompts to choose your mode, key, and message.

## 📚 Reference

- Based on Al Sweigart’s version in *The Big Book of Small Python Projects*
- [Wikipedia - Caesar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

## 🔄 Customization Ideas

- Add support for lowercase letters, numbers, and punctuation
- Integrate automated unit tests for encryption/decryption accuracy
- Build a GUI frontend with Tkinter for beginner-friendly use
- Create batch file processing capabilities for multiple messages
- Implement frequency analysis to crack Caesar-encrypted texts
