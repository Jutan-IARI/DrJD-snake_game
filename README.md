# 🐍 Snake Game by Dr. Jutan Das

A fun, visually interactive Snake Game created by **Dr. Jutan Das** using Java and HTML/CSS/JavaScript.

The game has a biology-inspired theme where the snake eats **frogs 🐸** to grow and occasionally gets a **rat 🐀 bonus** for extra points.

---

## 🎮 Play the Game

👉 **[Play Snake Game Online](https://jutan-iari.github.io/DrJD-snake_game/)**

No Java installation or programming knowledge is required to play the online version.

---

## ✨ Features

- 🐍 Animated snake
- 🐸 Frog as the normal food
- 🐀 Rat as the bonus food
- 📈 Snake grows after eating frogs
- ⭐ Bonus points for eating the rat
- 🔄 Snake wraps around the walls
- 💀 Game ends when the snake hits its own body
- ⏱️ Limited-time bonus rat
- 🎮 Keyboard controls
- ⏸️ Pause and resume
- 🔁 Restart option
- 📱 Browser-based version
- 🌐 Playable directly through GitHub Pages

---

## 🕹️ Controls

| Key | Action |
|---|---|
| ⬆️ Up Arrow | Move Up |
| ⬇️ Down Arrow | Move Down |
| ⬅️ Left Arrow | Move Left |
| ➡️ Right Arrow | Move Right |
| W | Move Up |
| S | Move Down |
| A | Move Left |
| D | Move Right |
| Space | Pause / Resume |
| R | Restart after Game Over |

---

## 🐸 Game Rules

### Frog 🐸

Eat the frog to:

- Increase your score
- Increase the snake's length
- Generate a new frog at another position

### Rat 🐀 Bonus

After eating **5 frogs**, a rat appears as a bonus.

The rat:

- Gives **+5 bonus points**
- Appears only for a limited time
- Disappears if it is not eaten in time
- Gives the snake an additional challenge

---

## 🧠 Game Over

The game does **not** end when the snake touches the wall.

Instead, the snake wraps around:

```text
Top → Bottom
Bottom → Top
Left → Right
Right → Left
