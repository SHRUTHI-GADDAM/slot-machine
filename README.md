# 🎰 Python Slot Machine

A simple command-line Slot Machine game built with Python. Players can deposit money, place bets on multiple lines, spin the slot machine, and win rewards based on matching symbols.

---

## 📌 Features

* 💰 Deposit an initial balance
* 🎲 Bet on 1 to 3 lines
* 🎰 Random slot machine spins
* 🏆 Automatic win detection
* 💵 Balance updates after every spin
* ✅ Input validation for deposits and bets
* 🔁 Play multiple rounds until you choose to quit or run out of balance

---

## 🛠️ Built With

* Python 3
* `random` module

---

## 📂 Project Structure

```
slot-machine/
│── main.py
│── README.md
```

---

## ▶️ Getting Started

### Clone the repository

```bash
git clone https://github.com/SHRUTHI-GADDAM/slot-machine.git
```

### Navigate to the project

```bash
cd slot-machine
```

### Run the game

```bash
python main.py
```

---

## 🎮 How to Play

1. Deposit an initial amount.
2. Choose the number of lines to bet on (1–3).
3. Enter your bet amount per line.
4. Spin the slot machine.
5. Win if all symbols on a selected line match.
6. Continue playing until you decide to quit or your balance reaches zero.

---

## 🎯 Game Rules

### Symbol Distribution

| Symbol | Count | Multiplier |
| ------ | ----: | ---------: |
| A      |     2 |         5x |
| B      |     4 |         4x |
| C      |     6 |         3x |
| D      |     8 |         2x |

* Rarer symbols offer higher rewards.
* Winnings are calculated as:

```
Winning = Symbol Multiplier × Bet per Line
```

---

## 📷 Example Output

```
Current balance: $100

You are betting $10 on 3 lines.
Total bet = $30

A | B | C
A | A | A
D | C | B

You won: $50
Winning lines: [2]

Current balance: $120
```

---

## 🚀 Future Improvements

* 🎨 Graphical user interface (Tkinter or Pygame)
* 💾 Save player balance
* 🔊 Sound effects
* 🎁 Bonus rounds
* 💎 Jackpot feature
* 📊 Statistics and game history

---

## 📚 Concepts Used

* Functions
* Loops
* Dictionaries
* Lists
* Randomization
* Input validation
* Conditional statements
* Modular programming

---

## 👩‍💻 Author

**Shruthi Gaddam**

GitHub: https://github.com/SHRUTHI-GADDAM

---

## 📄 License

This project is intended for learning and educational purposes.
