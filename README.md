# 🐍 Snake Game — OOP Edition

A classic **Snake Game built in C++** using **Object-Oriented Programming (OOP)** concepts and the Windows Console API.

The player controls a snake using the keyboard, collects food to increase the score and snake length, and must avoid colliding with the walls or the snake's own body.

---

## 🎮 Gameplay

The objective is simple:

- Control the snake using **W, A, S, D**
- Eat the `*` food to increase your score
- Each food item increases the snake's length
- Avoid hitting the walls
- Avoid colliding with the snake's own body
- Press **P** to pause or resume the game
- Try to achieve the highest score possible

### Controls

| Key | Action |
|-----|--------|
| `W` | Move Up |
| `S` | Move Down |
| `A` | Move Left |
| `D` | Move Right |
| `P` | Pause / Resume |

---

## ✨ Features

- Real-time keyboard input
- Smooth console-based movement
- Random food generation
- Snake growth after eating food
- Live score tracking
- Pause and resume functionality
- Wall collision detection
- Self-collision detection
- Colored console graphics
- Hidden console cursor for cleaner gameplay
- Start screen and game-over screen
- Constant game speed
- Object-oriented architecture

---

## 🧠 OOP Concepts Used

This project demonstrates several important C++ Object-Oriented Programming concepts.

### 1. Abstraction

The `Drawable` class acts as an abstract base class:

```cpp
class Drawable {
public:
    virtual void draw() const = 0;
    virtual ~Drawable() {}
};
