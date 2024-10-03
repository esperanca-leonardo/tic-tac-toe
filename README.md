# 🕹️ Tic-Tac-Toe Game in Java
Tic-Tac-Toe Game in Java is a console-based application developed in Java that allows two players to engage in a game of Tic-Tac-Toe. Utilizing basic logic, the application manages player turns, validates moves, checks for winning conditions, and declares the game outcome.


## 📑 Table of Contents
- [Key Features]()
- [Demonstration Video]()
- [How It Works]()
- [Tools and Technologies Used]()
- [Prerequisites]()
- [Installation Instructions]()
    - [Clone this repository]()
    - [Navigate to the project directory]()
    - [Compile the project]()
    - [Run the application]()
- [Observations]()
- [License]()
- [Contributions]()

## 🚀 Key Features
- **Console Interface:** Simple and intuitive, allowing easy interaction via the terminal.
- **Move Management:** Alternates between players 'X' and 'O', recording chosen positions.
- **Win Condition Checking:** Automatically detects winning conditions by rows, columns, or diagonals.
- **Draw Detection:** Recognizes when all positions are filled without a winner.
- **Ease of Use:** Minimalist design, ideal for quick entertainment and learning purposes.

## 💡 How It Works
- **Board Initialization:**
    - The game starts with an empty 3x3 board, represented by blank spaces.
- **Player Alternation:**
    - Two players take turns, choosing positions on the board by entering row and column coordinates.
- **Move Registration:**
    - After each move, the board is updated and displayed in the console.
- **Win Condition Verification:**
    - After each move, the game checks if the current player has completed a row, column, or diagonal with their symbol.
- **Draw Detection:**
    - If all positions are filled without any player winning, the game declares a draw.
- **Game Termination:**
    - The game ends when a player wins or a draw occurs, displaying the corresponding message.
 
## 🔧 Tools and Technologies Used
- **Java:** A robust and widely-used programming language, ideal for building console applications.
- **IDE (Optional):** Integrated Development Environment for writing and debugging Java code.
- **Git:** Version control system for managing and collaborating on the project.

## 📋 Prerequisites
Before running the application, ensure you have the following prerequisites installed:
- **Java Development Kit (JDK) 8 or higher:** Required to compile and run Java applications.
- **Git:** (Optional) For cloning the repository.

## 📝 Installation Instructions
1. Clone this repository


## 📌 Observations
- **Board Customization:** To start with a different configuration, modify the board array in the App class.
- **Input Validation:** Currently, the game prompts for numerical inputs for row and column. Ensure to enter values between 0 and 2 to avoid invalid moves.
- **Extensibility:** Although currently a console application, the game can be extended with a graphical user interface (GUI) or additional features as needed.
