
```
# 🎮 Tic Tac Toe (Random Simulation)

This project is a simple Tic Tac Toe game simulation written in Python using NumPy.
Both players make random moves, and the game continues until a player wins or the board is full.

This is not an AI-based game. It is a random-move simulation created to demonstrate:
- Board representation using NumPy
- Game-state evaluation logic
- Modular function-based design

---

## 🧠 How the Game Works

- The board is a 3×3 NumPy array
- Player 1 is represented by 1
- Player 2 is represented by 2
- Empty cells are 0
- Each player chooses a random available cell
- The game checks for row, column, diagonal wins, or a draw

The board is printed after every move with a short delay so the game flow is visible.

---

## 📂 Project Structure

TIC_TAC_TOE/
│
├── tic_tac_toe.py
├── README.md

---

## ▶️ How to Run

1. Clone the repository
```

git clone [https://github.com/your-username/tic-tac-toe.git](https://github.com/your-username/tic-tac-toe.git)
cd tic-tac-toe

```

2. Install dependencies
```

pip install numpy

```

3. Run the game
```

python tic_tac_toe.py

```

---

## 🧩 Example Output

```

[[0 0 0]
[0 0 0]
[0 0 0]]

Board after move 1:
[[1 0 0]
[0 0 0]
[0 0 0]]

Winner is: 2

```

---

## 🚀 Possible Improvements

- Implement Minimax algorithm
- Add human vs computer mode
- Create a GUI using Tkinter or Pygame
- Run multiple simulations and track statistics

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- random, time modules

---



This is **GitHub-ready**.
Next upgrade should be logic-based moves (Minimax), not cosmetics.
