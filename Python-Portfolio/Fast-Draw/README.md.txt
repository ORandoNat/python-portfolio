# 🤠 Fast Draw — Reflex Test Game

Are you the fastest draw in the west?  
This tiny terminal game challenges your reflexes with dramatic flair. Wait for the "DRAW!" signal and see how quickly you can react — but press too early and it’s game over!

## 🔫 Gameplay Mechanics

- Wait in suspense for the signal...
- Press `Enter` within **0.3 seconds** after "DRAW!" appears
- Pressing `Enter` too early results in instant disqualification
- Fast enough? You win. Slow or jumpy? Try again!

## 🕹️ How to Play

```bash
python fast_draw.py
```

Follow the prompts.  
Press `Enter` when you see `"DRAW!"` — but not a moment sooner.

## 🛠 Technologies Used

- Python 3
- Standard libraries: `random`, `time`, `sys`

## 🧠 Learning Highlights

- Practiced timing logic using `time.time()`
- Implemented input gating with `input()` delays
- Explored user feedback based on response time
- Strengthened control flow for game loop and user prompts

## ⚡ Extension Ideas

- Add score tracking or leaderboard
- Include difficulty settings (shorter or longer time windows)
- Introduce visual ASCII cues or countdown
- Create a multiplayer mode with fastest reaction wins
- Test performance using simulated input for QA automation

