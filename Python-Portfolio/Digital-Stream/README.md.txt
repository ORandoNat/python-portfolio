# 🟩 Digital Stream — Matrix-Style Terminal Screensaver

A mesmerizing terminal animation reminiscent of the falling binary code from _The Matrix_. This screensaver-style script produces a cascade of random `1`s and `0`s across the screen, simulating an endless digital rain effect.

## 🧱 Core Features

- Randomized vertical streams across terminal columns
- Adjustable stream length, density, and update rate
- Uses only standard Python libraries
- Responsive to terminal size for flexible display
- Graceful exit with `Ctrl+C`

## 📦 Requirements

- **Python 3**
- Libraries used: `random`, `time`, `sys`, `shutil`

## 🚀 How to Run

```bash
python digital_stream.py
```

Sit back and enjoy the hypnotic fall of digital rain.

## 🔧 Configurable Parameters

| Constant            | Description                                      |
|---------------------|--------------------------------------------------|
| `MIN_STREAM_LENGTH` | Shortest stream before fade-out                  |
| `MAX_STREAM_LENGTH` | Longest possible stream                          |
| `PAUSE`             | Delay between each frame (lower = faster)        |
| `STREAM_CHARS`      | Characters used (default: `['0', '1']`)          |
| `DENSITY`           | Probability of stream starting in each column    |

You can tune these to mimic your preferred glitch aesthetic or Matrix vibe.

## 🧠 Learning Highlights

- Practiced dynamic terminal rendering with column control
- Used modular random logic for stream length and appearance
- Managed screen sizing and flow consistency across devices
- Explored flush buffering for real-time display updates

## 🌀 Customization Ideas

- Add `colorama` for green glow or fading tail effects
- Mix in alphanumeric or Unicode glyphs for hacker-style visuals
- Create multiple layers with varying speeds for depth
- Use as a terminal-based screensaver module or idle state background
- Add sound synchronization for immersive ambiance

