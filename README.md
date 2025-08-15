
---

# 🍓 Fruit Frenzy

**Fruit Frenzy** is a fast-paced OpenGL-based arcade game where you control a basket to catch fruits, avoid bombs, and grab eggs to regain lives. The goal is simple — score as high as possible before you run out of hearts!

---

## 🎮 Gameplay Overview

In **Fruit Frenzy**, fruits, bombs, and eggs fall from the top of the screen:

* **Catch Fruits** 🥝 – Increases your score.
* **Avoid Bombs** 💣 – Bombs cost you hearts.
* **Catch Eggs** 🥚 – Eggs restore your hearts (up to a maximum of 5).
* **Miss Too Many Fruits** 🍌 – Every 3 missed fruits costs you 1 heart.

The game ends when you lose all your hearts.

---

## 🕹 Controls

### **Keyboard**

| Key   | Action                 |
| ----- | ---------------------- |
| **A** | Move basket left       |
| **D** | Move basket right      |
| **P** | Pause/Unpause the game |
| **Q** | Quit the game          |

### **Mouse**

Hover over and click the **buttons** at the top-right:

* **Green** – Restart game
* **Blue** – Pause/Resume
* **Red** – Exit game

---

## 📜 Rules

1. **Fruits**

   * 🍎 **Apple**: +1 point
   * 🍌 **Banana**: +2 points
   * 🍇 **Grapes**: +3 points

2. **Bombs** 💣

   * If caught, you lose **2 hearts** instantly.

3. **Eggs** 🥚

   * Restores **1 heart** (up to a maximum of 5).

4. **Missed Fruits**

   * Every **3 missed fruits** costs you **1 heart**.

5. **Game Over**

   * Happens when **hearts reach 0**.

---

## 🖥 Installation & Running

### **Requirements**

Make sure you have **Python 3** installed, along with the following dependencies:

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

### **Run the Game**

```bash
python fruit_frenzy.py
```

---

## 📸 Game Window Layout

* **Top Left** – Score and missed fruits counter.
* **Top Center** – Hearts remaining.
* **Top Right** – Control buttons (Restart, Pause, Exit).
* **Bottom Center** – Your basket.

---

## 💡 Tips for High Score

* Focus on catching **high-value fruits** like grapes.
* Stay centered to react faster to falling objects.
* Avoid risky moves for eggs if a bomb is nearby.
* Remember, speed increases as your score rises!

---

## 📄 License

This project is open-source. You’re free to modify and distribute it, but please credit the original author.

---
