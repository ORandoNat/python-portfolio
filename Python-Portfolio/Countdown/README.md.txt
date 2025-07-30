# ⏱️ Countdown Timer — Seven-Segment Display Simulation

A terminal-based countdown timer using a custom seven-segment ASCII renderer. Inspired by retro digital clocks, this project offers an eye-catching, animated display for hours, minutes, and seconds — with a cinematic "BOOM" at the finale.

## 🔧 Features

- Dynamic countdown rendered in ASCII-style seven-segment digits
- Configurable starting time (default: 560 seconds)
- Graceful exit with `Ctrl+C`
- Visually spaced formatting mimicking LED display structure

## 📦 Requirements

- **Python 3**
- `sevseg.py` module included in the same directory  
  *(This module handles ASCII digit rendering. Not available via pip; must be custom-supplied.)*

## 🔍 Technologies Used

- `time` for precise countdown pacing  
- `sys` for system exit controls  
- `sevseg` for digit drawing and line-based layout  
- Modular breakdown of hours/minutes/seconds from total seconds

## 🚀 How to Run

1. Ensure `sevseg.py` is in the same folder.
2. Run the script:

```bash
python countdown.py
```

3. Watch the timer drop to zero, then enjoy the dramatic ending.

## 🧪 Learning Highlights

- Practiced modular import and inter-script functionality
- Implemented time arithmetic for converting seconds to H:M:S
- Created layout logic for multi-line ASCII digits
- Explored terminal-friendly animation techniques
- Used graceful exception handling for user interruption

## 🎯 Customization Ideas

- Tweak `secondsLeft` to change duration
- Add sound playback on completion using `playsound` or `pygame`
- Add color via `colorama` or transition effects with `curses`
- Wrap in a GUI using `tkinter` or `PyQt`
- Write unit tests for time conversion logic (great QA exercise)
