# 🪐 Asteroids

A simple arcade-style Asteroids game built with Python and Pygame.

Control your ship, dodge incoming asteroids, and blast them into smaller pieces—until they’re gone for good.

## 🎮 Controls

- `W` / `A` / `S` / `D` — Move the ship
- `Spacebar` — Shoot projectiles

Asteroids break into smaller pieces when hit. The smallest ones are destroyed entirely.

## 🚀 How to Run the Game

This project uses `uv` for dependency management and packaging.

1. Clone the Repository

   ```bash
   git clone https://github.com/emilyjanedev/asteroids.git
   cd asteroids
   ```

2. Install Dependencies

   If you don't have uv installed:

   ```bash
   pip install uv
   ```

   Then install dependecies:

   ```bash
   uv pip install -r requirements.txt
   ```

3. Run the Game

   ```bash
   uv run main.py
   ```

## 🧩 Dependencies

- Python 3.10+
- [Pygame](https://www.pygame.org/news)
