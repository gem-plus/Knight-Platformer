# 🧙 Knight Platformer

A 2D platformer game built with **Godot 4.4** as part of my game development learning journey.

Play as a knight, collect coins, dodge slimes, and survive as long as you can!

---

## 🎮 Gameplay

- Run and jump across platforms
- Collect coins to increase your score
- Avoid slimes — they patrol platforms and will kill you on contact
- Fall into a kill zone and the scene resets (with a slow-motion death effect!)

---

## 🕹️ Controls

| Action | Key |
|--------|-----|
| Move Left | `A` or `←` |
| Move Right | `D` or `→` |
| Jump | `Space` or `↑` |

---

## ✨ Features

- Smooth player movement with idle, run, and jump animations
- Sprite flipping based on movement direction
- Slime enemies with raycasted patrol AI (auto-reverse at platform edges)
- Coin collectibles with pickup animation and sound
- Score tracker ("You collected X coins")
- Background music (autoloaded across scenes)
- Sound effects: jump, land, coin pickup, power-up, hurt, explosion
- Death mechanic with slow-motion effect and scene reload
- Pixel art assets and PixelOperator font for authentic retro feel

---

## 🗂️ Project Structure

```
├── assets/
│   ├── fonts/          # PixelOperator pixel fonts
│   ├── music/          # Background music
│   ├── sounds/         # SFX (jump, coin, hurt, etc.)
│   └── sprites/        # Knight, slimes, coins, tiles, platforms
├── scenes/
│   ├── game.tscn       # Main game scene
│   ├── player.tscn     # Player character
│   ├── slime.tscn      # Slime enemy
│   ├── coin.tscn       # Collectible coin
│   ├── killzone.tscn   # Death trigger area
│   ├── music.tscn      # Autoloaded music manager
│   └── ...             # Platform and decoration scenes
└── scripts/
    ├── player.gd       # Player movement, animation, sounds
    ├── slime.gd        # Slime patrol AI
    ├── coin.gd         # Coin pickup logic
    ├── killzone.gd     # Death + scene reload logic
    └── gameManager.gd  # Score tracking
```

---

## 🛠️ Built With

- [Godot Engine 4.4](https://godotengine.org/) — GL Compatibility renderer
- GDScript
- Free pixel art assets

---

## 🚀 How to Run

1. Download and install [Godot 4.4](https://godotengine.org/download)
2. Clone this repository:
   ```bash
   git clone https://github.com/gem-plus/Knight-Platformer
   ```
3. Open Godot → **Import Project** → select the `project.godot` file
4. Hit **Play** ▶️

---

## 📚 About

This is my first self-built game project, developed while learning Godot and game development fundamentals. It covers core concepts like scene management, physics-based movement, area detection, animation state machines, and audio management.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
