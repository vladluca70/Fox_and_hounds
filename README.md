# 🦊 Fox and Hounds – C++ Strategy Game

Welcome to **Fox and Hounds**, a strategy-based board game implemented in **C++** using the `graphics.h` library! 🎮  
The game combines **classic logic gameplay** with a **modern neon-green aesthetic**, delivering both fun and visual appeal. 💡🟢

---

## 🎮 Game Concept

**Fox and Hounds** is a classic board game where:
- You play as either the **Fox** or the **Hounds**.
- The **Fox** starts at the **bottom row**.
- The **5 Hounds** start at the **top row**.
- All pieces move **diagonally**, one cell per move.

### 🦊 Fox Objective:
> Move from the **first row (bottom)** to the **eighth row (top)** without being **trapped** by the Hounds.

### 🐶 Hounds Objective:
> Block the **Fox** and prevent it from reaching the top row by **coordinating** movement.

---

## 🖼️ Interface

✨ The interface is built using **graphics.h**, offering:
- A **neon green + black theme** 🌌
- A **user-friendly layout**
- Intuitive piece movement and turn-based logic
- A dedicated **instructions screen** for new players 📝

---

## 🎚️ Difficulty Levels

The game includes **three difficulty levels** to challenge players of all skill levels:

| Level | Behavior |
|-------|----------|
| 🟢 Easy   | Hounds move **completely random** |
| 🟡 Medium | One **good decision**, followed by a **random one** |
| 🔴 Hard   | Hounds make **only correct moves** using well-studied logic |

Each level introduces progressively smarter AI behavior, making the game more strategic and engaging.

---

## 📦 Technologies Used

- 🧠 **Language**: C++
- 🖼️ **Graphics**: `graphics.h`
- 🧰 **Compiler**: Turbo C++ / WinBGIm-compatible environments

---

## 🧪 How to Run

To run the game, make sure you have a C++ compiler that supports `graphics.h` (such as WinBGIm):

```bash
# Compile
g++ -o fox_and_hounds.exe main.cpp -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

# Run
./fox_and_hounds.exe
```

## 🛠️ Features
🧩 Turn-based logic  
🎨 Custom-designed UI with neon color scheme  
🧠 AI-based difficulty scaling  
📖 Instruction screen included  
✅ Clean code separation and modular design  

---

## 🧠 Final Thoughts
Creating this game was a fun and rewarding way to apply C++ and graphical programming concepts!  
From basic game loops to AI-based decisions, this project pushed my understanding of both OOP and game logic design.

🔗 Built with ❤️, C++, and a passion for strategy games.
