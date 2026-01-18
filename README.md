# Tic Tac Toe – Java Console Application (JAR)

This project is a **console-based Tic Tac Toe game** developed using **Core Java**.  
It is packaged as an **executable JAR file** and can be run on any PC that has Java installed.

The game supports **two players (X and O)**, validates input using **custom exceptions**, and automatically restarts after a **win or draw**.

---

## 📌 System Requirements

- Java **JDK 8 or above**
- Command Prompt / Terminal
- Windows / Linux / macOS

### Verify Java Installation

java -version
📂 Project Files
TicTacToe.jar – Executable Java JAR file

README.md – Instructions to run and play the game

▶️ How to Run the Game (JAR File)
Step 1: Open Command Prompt / Terminal
Navigate to the directory where TicTacToe.jar is located.

Example (Windows):

cd D:\Java\TicTacToe
Step 2: Run the JAR File
java -jar TicTacToe.jar
Step 3: Game Starts
You will see:

**** GAME START ****
The Tic Tac Toe grid will be displayed in the console.

🎮 How to Play the Game
Players
Player X starts the game

Player O plays next

Players take turns

Input Format (Very Important)
Players must enter their move in RowColumn format:

Input	Description
A1	Row A, Column 1
B2	Row B, Column 2
C3	Row C, Column 3
Rows: A, B, C
Columns: 1, 2, 3

Example Gameplay
Enter your response X : A1
Enter your response O : B2
Enter your response X : A2
❌ Invalid Input Handling (Custom Exception)
This application uses a custom exception (InvalidMoveException) to safely handle invalid inputs.

Examples of Invalid Inputs
a

A

D4

A5

Selecting an already occupied cell

Error Message Example
ERROR: Input must be exactly like A1, B2, or C3
✔ The game does not crash
✔ Player is asked to enter input again

🏆 Winning Rules
A player wins if they mark three identical symbols in:

Any row

Any column

Any diagonal

Winner Message Example
X is winner
or

O is winner
🤝 Draw Condition
If:

All cells are filled

No player has won

The game prints:

DRAW
🔄 Automatic Game Restart
After a win or a draw, the game restarts automatically

No need to rerun the JAR file

A fresh 3×3 board is created each time

🧠 Concepts Used
Core Java

2D Arrays

Loops and Conditional Statements

Custom Exceptions

Exception Handling

Scanner (User Input)

Console Output Formatting

JAR File Creation and Execution

⚠️ Important Notes
This is a console-based application

No GUI (Swing / JavaFX) is used

Input is case-insensitive (a1 → A1)

Program is designed for learning and practice

👨‍💻 Project Purpose
This project was developed as part of Core Java practice, focusing on:

Logical thinking

Input validation

Exception handling

Real-world Java execution using JAR files

✅ Conclusion
This Tic Tac Toe application demonstrates how a Java program can be:

Executed using a JAR file

Made robust using custom exceptions

Designed with clean game flow logic

Enjoy playing the game!


---

```If you want next:
- `README.md` **short exam version**
- **GitHub professional README**
- Add **screenshots section**
- Add **build steps (javac → jar)**

Just tell me what you want.
