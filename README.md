# 🐍 Snake Game (C++ Console Version)

This is a simple Snake Game built using **C++** for the Windows console.  
The game uses **emoji graphics** to make the gameplay fun and visually clear.

---

## 🎮 Gameplay

- Control the snake and collect **apples (🍎)** to increase your score.
- Avoid **rocks (🪨)** — hitting one ends the game.
- Avoid **walls** and your own body — touching them causes game over.
- If you hit a **bomb (💣)**:
  - You lose **20 points**
  - The snake **shrinks**
  - The bomb respawns somewhere else

---

## 🕹 Controls

| Key | Action     |
|-----|------------|
| **W** | Move Up    |
| **S** | Move Down  |
| **A** | Move Left  |
| **D** | Move Right |
| **X** | Exit Game  |

> The snake cannot instantly reverse direction (e.g., Left → Right) to prevent accidental self-collision.

---

## ⭐ Scoring

| Event | Effect |
|------|--------|
| 🍎 Eat Apple | **+10 points**, snake grows |
| 💣 Hit Bomb | **-20 points**, snake shrinks |
| 🪨 Hit Rock | **Game Over** |
| Hit Wall / Self | **Game Over** |

At game over, the following stats are shown:
- **Apples Eaten**
- **Bombs Hit**
- **Final Score**

---

## ⚙️ Compile & Run

Open terminal in the folder where `snake.cpp` is saved:

```bash
g++ snake.cpp -o snake.exe
./snake.exe
