# 🎮 Rock Paper Scissors Game

A desktop-based Rock Paper Scissors game developed using **Python and PyQt5**. The application allows users to play against the computer through an interactive graphical user interface (GUI).

The computer randomly selects Rock, Paper, or Scissors, and the application determines the winner based on the game rules.

## 📌 Project Overview

This project is a GUI-based implementation of the classic Rock Paper Scissors game.

Users can select one of three options:
- 🪨 Rock
- 📄 Paper
- ✂️ Scissors

The computer randomly generates its choice after a countdown, and the application automatically displays the result: User Wins, Computer Wins, or Draw Match.

A Reset button allows users to start a new game.

## ✨ Features

- Interactive graphical user interface.
- Play against the computer.
- Random computer selection.
- Countdown mechanism using QTimer.
- Automatic winner determination.
- Visual representation of Rock, Paper, and Scissors.
- Reset functionality to play multiple rounds.
- Button controls to prevent multiple selections during a round.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| PyQt5 | GUI development |
| Random | Generate random computer choices |
| QTimer | Implement countdown functionality |
| Sys | Application execution and exit handling |

## 📂 Project Structure

```text
Rock-Paper-Scissors/
│
├── codsoft2.py
├── rock.png
├── Paper.png
├── scissor.png
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Execution

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Rock-Paper-Scissors
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Alternatively, install PyQt5 directly:

```bash
pip install PyQt5
```

**Note:** Random and Sys are built-in Python modules and do not require separate installation.

### 4. Run the Application

```bash
python codsoft2.py
```

## 🎯 How to Play

1. Launch the application.
2. Select Rock, Paper, or Scissors.
3. The selected option will appear on the user's side.
4. A countdown begins before the computer reveals its choice.
5. The application compares both selections.
6. The result is displayed:
   - **User Wins:** The user's selection beats the computer's selection.
   - **Computer Wins:** The computer's selection beats the user's selection.
   - **Draw Match:** Both selections are identical.
7. Click the **Reset** button to start another round.

## 📖 Game Rules

| User Choice | Computer Choice | Result |
|---|---|---|
| Rock | Scissors | User Wins |
| Rock | Paper | Computer Wins |
| Paper | Rock | User Wins |
| Paper | Scissors | Computer Wins |
| Scissors | Paper | User Wins |
| Scissors | Rock | Computer Wins |
| Same Choices | Same Choices | Draw Match |

## 🧠 Concepts Implemented

- Object-Oriented Programming (OOP).
- Python classes and objects.
- Conditional statements.
- Functions and methods.
- Random number generation.
- Event-driven programming.
- Signal and slot mechanism in PyQt5.
- Timer-based execution using QTimer.
- GUI components such as labels and push buttons.

## 🚀 Future Enhancements

- Add score tracking for multiple rounds.
- Include sound effects for user interactions.
- Improve the graphical interface with modern styling.
- Add animations during the countdown.
- Display match history.
- Add a best-of-five game mode.

## 👩‍💻 Author

**Swathi Nandiraju**

Developed as a Python programming project to strengthen practical knowledge of Python, object-oriented programming, GUI development, and event-driven programming.

---

⭐ If you find this project interesting, consider giving the repository a star!
