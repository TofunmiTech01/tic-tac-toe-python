<p align="center">
  <img src="images/tictactoe_cover.png" width="300"/>
</p>

# 🎮 Tic Tac Toe — Python Terminal Game

A simple, interactive **two-player Tic Tac Toe game** built in Python and played in the terminal.  
This project demonstrates core programming concepts such as **functions, lists, loops, conditionals, and input validation**.

---

## 🧩 Features

- Two-player gameplay (**X** vs **O**)  
- Clean 3×3 board layout  
- Prevents invalid or duplicate moves  
- Winner detection (rows, columns, diagonals)  
- Draw detection  
- Replay option  
- Simple and readable code structure  

---

## 📁 Project Structure

```
📂 Tic-Tac-Toe
│
├── TIC TAC TOE.ipynb
├── images/
│   └── tictactoe_cover.png   # Game image
└── README.md
```

---

## ▶️ How to Run the Game

Clone the repo:

```
git clone https://github.com/your-username/python-tic-tac-toe-game.git
```

Open the notebook:

```
jupyter notebook "TIC TAC TOE.ipynb"
```

Run all cells and start playing!

---

## 🧠 How the Game Works

### **1. Board**
Stored as a list of numbers (1–9).  
Numbers are replaced by `"X"` or `"O"` during the game.

### **2. Display**
A function prints the board in a clear 3×3 grid.

### **3. Player Input**
Ensures:
- Input is a number  
- Within range  
- Not already played  

### **4. Winner Check**
Checks:
- 3 rows  
- 3 columns  
- 2 diagonals  

### **5. Draw Check**
Board full + no winner = draw.

### **6. Game Loop**
Controls:
- Player switching  
- Board updates  
- Win/draw checks  

### **7. Replay**
Players can restart after finishing.

---

## 🎮 How to Play

1. Run the notebook  
2. Player **X** goes first  
3. Enter any number **1–9** to place your mark  
4. Players alternate turns  
5. First to get **3 in a row** wins  
6. If the board fills up with no winner → **Draw**  
7. After the result, choose whether to play again

---

## 🚀 Technologies Used
- Python 3  
- Jupyter Notebook  

---

## 🏁 Future Improvements

- Add Tkinter GUI  
- Add AI opponent (Minimax)  
- Add colors to terminal  
- Convert to standalone `.py` script

---

## 👤 Author
**Oluwatofunmi Ishola**

Feel free to ⭐ the repo!



