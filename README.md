# Asteroids Clone (Python + Pygame)

A classic-style **Asteroids** arcade game built using Python and Pygame. Control a spaceship, dodge and destroy asteroids, and survive as long as you can!

---

## 🚀 Features

- Smooth 2D space movement with rotation and thrust
- Bullet shooting with cooldown timer
- Asteroids split into smaller chunks when hit
- Vector-based movement and collision detection

---

## 🎮 Controls

| Key           | Action              |
|---------------|---------------------|
| Left Arrow    | Rotate Left         |
| Right Arrow   | Rotate Right        |
| Up Arrow      | Thrust Forward      |
| Down Arrow    | Thrust Backward     |
| Spacebar      | Shoot Bullet        |

---

## 🛠️ Requirements

- Python 3.x
- Pygame 2.6.1

Install dependencies with:
```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Game

Run the game with:
```bash
python main.py
```

---

## 🧱 Project Structure

```
.
├── main.py               # Entry point for the game
├── constants.py          # Game constants (screen size, speeds, etc.)
├── circleshape.py        # Base class for all circular game objects
├── player.py             # Player spaceship logic
├── shot.py               # Bullet logic
├── asteroid.py           # Asteroid behavior and splitting
├── asteroidfield.py      # Spawner for initial asteroids
├── requirements.txt      # Dependencies list
```

---

## 📦 Future Improvements

- Add score tracking
- Explosion animations and sound effects
- Lives system or health bar
- Game over and restart screen

---

## 🧑‍💻 Credits

Created as a Python/Pygame project. Inspired by the original Asteroids arcade game.

---

Enjoy blasting some rocks! ✨

