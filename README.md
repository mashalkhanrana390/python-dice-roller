# 🎲 Python Dice Roller

A simple and beginner-friendly **Dice Roller application built with Python**.
This project simulates rolling a six-sided dice and generates a random number between **1 and 6**.

The project is designed to practice important Python programming concepts such as **functions, loops, conditions, user input, and the random module**.

---

## 📌 Project Overview

The Dice Roller allows the user to roll a virtual dice repeatedly.

* Press **Enter** to roll the dice.
* A random number between **1 and 6** is generated.
* Press **`q`** to quit the program.
* The program continues running until the user chooses to exit.

---

## ✨ Features

* 🎲 Random dice roll from **1 to 6**
* 🔄 Roll the dice multiple times
* ⌨️ Simple user input
* 🚪 Press `q` to exit
* 🧩 Custom `roll_dice()` function
* 📦 Uses Python's built-in `random` module
* 👨‍💻 Beginner-friendly project

---

## 🛠️ Technologies Used

* **Python 3**
* **Random Module**
* **VS Code** (recommended)

No external packages are required.

---

## 🧠 Python Concepts Practiced

This project helps practice:

* Variables
* Functions
* `def`
* `return`
* `import`
* Random numbers
* `random.randint()`
* `input()`
* `print()`
* `while` loop
* `if` statement
* `break`
* String methods
* f-strings
* Docstrings

---

## 📂 Project Structure

```text
python-dice-roller/
│
├── dice_roller.py
└── README.md
```

---

## 💻 Source Code

```python
import random

print("=================================")
print("           DICE ROLLER")
print("=================================")

def roll_dice():
    """Rolls a dice and returns a random number between 1 and 6."""
    return random.randint(1, 6)


# Main program
print("== Welcome To Dice Roller ==")

while True:
    choice = input("Press Enter to roll the dice (or 'q' to quit): ")

    if choice.lower() == "q":
        print("Thanks for playing! Goodbye...")
        break

    result = roll_dice()
    print(f"You rolled: {result}")
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/python-dice-roller.git
```

### 2. Open the project folder

```bash
cd python-dice-roller
```

### 3. Run the Python file

```bash
python dice_roller.py
```

---

## 🖥️ Example Output

```text
=================================
           DICE ROLLER
=================================
== Welcome To Dice Roller ==

Press Enter to roll the dice (or 'q' to quit):
You rolled: 4

Press Enter to roll the dice (or 'q' to quit):
You rolled: 2

Press Enter to roll the dice (or 'q' to quit):
You rolled: 6

Press Enter to roll the dice (or 'q' to quit): q
Thanks for playing! Goodbye...
```

---

## 🔍 How the Program Works

### Step 1: Import the random module

```python
import random
```

The `random` module allows Python to generate random values.

### Step 2: Create the dice function

```python
def roll_dice():
    return random.randint(1, 6)
```

The function generates a random number between **1 and 6**.

### Step 3: Get user input

```python
choice = input("Press Enter to roll the dice (or 'q' to quit): ")
```

The user can press **Enter** to roll or type **`q`** to quit.

### Step 4: Check for quit

```python
if choice.lower() == "q":
    break
```

If the user enters `q`, the loop stops.

### Step 5: Roll the dice

```python
result = roll_dice()
```

The function is called and the random result is stored in `result`.

### Step 6: Display the result

```python
print(f"You rolled: {result}")
```

The dice result is displayed on the screen.

---

## 📚 Functions Used

| Function           | Purpose                              |
| ------------------ | ------------------------------------ |
| `print()`          | Displays information                 |
| `input()`          | Gets input from the user             |
| `roll_dice()`      | Custom function for rolling the dice |
| `random.randint()` | Generates a random number            |
| `choice.lower()`   | Converts input to lowercase          |

---

## 🎯 Learning Goal

The main goal of this project is to strengthen Python fundamentals by building a small real-world project.

It is especially useful for beginners learning:

**Python → Functions → Loops → Conditions → Random Module → Projects**

---

## 🚀 Future Improvements

Possible future features:

* 🎲 Roll two dice
* 📊 Count total rolls
* 🏆 Track the highest roll
* 📈 Show roll statistics
* 🎨 Add a graphical interface
* 🔊 Add sound effects
* 👥 Add multiplayer mode
* 🎯 Add a dice game mode

---

## 👨‍💻 Author

**Mashal Khan**

BS Artificial Intelligence Student
Python Learner & AI Enthusiast

---

## ⭐ Support

If you found this project useful for learning Python, consider giving the repository a ⭐ on GitHub.

---

## 📜 License

This project is created for **educational and learning purposes**.
