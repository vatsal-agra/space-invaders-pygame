# Space Invaders

A fully featured Space Invaders arcade game built from scratch in Python — complete with a home screen, multiple levels, a coin economy, and an in-game shop.

## Features

- **Home Screen** — level display, enemy count, and upgrade shop before each round
- **Multiple Levels** — enemies increase in number and speed as you progress
- **Coin Economy** — earn coins by defeating enemies, spend them on upgrades
- **2x Bullet Speed Upgrade** — purchasable in the shop for 650 coins
- **Sound Effects** — shooting, explosion, and background music
- **Score & Target Tracking** — live score and target display during gameplay
- **Game Over & Win States** — full end-game screens

## Tech Stack

- **Python**
- **Pygame** — game engine, rendering, input handling, sound
- **Pygame Mixer** — audio playback

## Required Files

All of the following must be in the same folder as the Python script:

| File | Purpose |
|------|---------|
| `rocket.png` | Window icon |
| `space-invaders.png` | Player ship sprite |
| `alien (1).png` | Enemy sprite |
| `bullet.png` | Bullet sprite |
| `background.png` | Game background |
| `play.png` | Play button on home screen |
| `2X SPEED (2).png` | Speed upgrade button |
| `maxed.png` | Displayed when bullet speed is maxed |
| `background.wav` | Background music |
| `laser.wav` | Shooting sound effect |
| `explosion.wav` | Enemy kill sound effect |

## How to Run

```bash
# Install dependencies
pip install pygame

# Run the game
python space_invaders.py
```

## Controls

| Action | Key |
|--------|-----|
| Move Left | A or ← |
| Move Right | D or → |
| Shoot | SPACE |

## Key Concepts Demonstrated

- Game loop architecture
- Collision detection using Euclidean distance
- Sprite and asset management
- Multi-level progression logic
- Coin economy and in-game purchasing system
- Sound integration with Pygame Mixer

---

**Author:** Vatsal Agrawal  
**GitHub:** [github.com/vatsal-agra](https://github.com/vatsal-agra)  
**LinkedIn:** [linkedin.com/in/vatsal-agrawal-a7a9641b0](https://linkedin.com/in/vatsal-agrawal-a7a9641b0)
