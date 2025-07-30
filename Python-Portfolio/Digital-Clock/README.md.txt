# ⏰ Digital Clock — Seven-Segment ASCII Time Display

A terminal-based digital clock that emulates classic seven-segment displays using Python. This artistic project pulls system time and renders each tick in ASCII form, creating a retro yet real-time clock that updates once per second.

## 🔧 Features

- Real-time 12-hour clock rendered in ASCII seven-segment format
- Modular rendering via `sevseg.py` digit formatting
- Clean CLI presentation with clear digit separation and blinking colons
- Uses system time for accuracy
- Graceful shutdown via `Ctrl+C`

## 📦 Requirements

- Python 3
- `sevseg.py` (must be in the same folder; handles ASCII digit creation)

## 🧠 Learning Highlights

- Practiced extracting and formatting current system time
- Implemented time loop logic for smooth updates
- Used modular code (`sevseg`) for display logic separation
- Built multi-line terminal render using split digit rows
- Explored edge case handling (e.g. converting “0” hours to “12”)

## 🚀 How to Run

```bash
python digital_clock.py
```

Watch your terminal turn into a ticking digital timepiece. Press `Ctrl+C` to quit.

## 🎨 Customization Ideas

- Switch to 24-hour clock (remove `hours % 12` conversion)
- Add blinking effect or color using `colorama`
- Include AM/PM indicator
- Extend to show date or timezone
- Wrap in a GUI shell or add sound beeps
- Add unit tests for clock conversion logic and display format

