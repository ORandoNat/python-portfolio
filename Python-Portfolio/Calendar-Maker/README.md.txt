# 📅 Calendar Maker — Custom Monthly Calendars in Python

A utility script written in Python that generates a text-based calendar for any specified month and year. This printable calendar format is perfect for quick reference, basic planning, or even command-line creativity.

## 📦 Overview

Prompt the user for a year and month, then generate a well-structured calendar formatted with week rows, day labels, and clean spacing. The output is displayed in the terminal and saved to a `.txt` file for reuse or printing.

## 🛠️ Features

- User input validation for year and month
- Flexible layout with week dividers and day cells
- Utilizes Python’s built-in `datetime` and `timedelta` modules
- Automatically rolls back to the nearest Sunday to begin layout
- Saves calendar to a uniquely named text file (`calendar_YYYY_MM.txt`)

## 🚀 Technologies Used

- Python 3
- `datetime` for date calculations
- `file handling` for saving output

## 🧠 Learning Highlights

- Worked with Python’s `datetime.date` and `datetime.timedelta`
- Built a dynamic loop for rolling through calendar weeks
- Reinforced string formatting and right alignment for clean display
- Practiced modular function design (`getCalendarFor`)
- Used file I/O to persist generated content

## 📦 How to Run

```bash
python calendar_maker.py
```

Follow the prompts to enter a year and month. The calendar will be printed and saved as a `.txt` file.

## 🔄 Customization Ideas

- Abbreviate days (e.g., SUN, MON) for compact output
- Add task boxes or notes rows beneath each day
- Generate full-year calendars in batch
- Implement color-coding or ANSI styling in terminal
- Unit-test `getCalendarFor` to practice QA workflows

## 📚 Reference

- Based on Al Sweigart’s *Big Book of Small Python Projects*
- [Python datetime documentation](https://docs.python.org/3/library/datetime.html)
