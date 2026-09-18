# 🎮 TicTacToeAB — Tic-Tac-Toe with AI

<p align="center">
  <em>Tic-Tac-Toe in Python with a graphical interface and artificial intelligence based on Minimax with Alpha-Beta pruning.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pygame-2.0%2B-green?style=flat" alt="Pygame">
  <img src="https://img.shields.io/badge/AI-Minimax%20%2B%20Alpha--Beta-purple?style=flat" alt="Minimax with Alpha-Beta pruning">
  <img src="https://img.shields.io/badge/status-in%20development-yellow?style=flat" alt="Status: in development">
</p>

---

**TicTacToeAB** implements the classic Tic-Tac-Toe game with a graphical interface built with Pygame. The player controls the `X` pieces, while the artificial intelligence uses `O` and selects its moves using the Minimax algorithm with Alpha-Beta pruning.

The AI analyzes possible future board states with the support of a heuristic function, seeking to increase its chances of winning and reduce the opponent's opportunities.

## 🎯 Objective

Provide an educational project to study concepts of artificial intelligence applied to games, recursion, decision-tree search, state evaluation, and graphical interface development with Python.

## ✨ Features

- Match between a human player and artificial intelligence.
- Graphical interface with mouse-click interaction.
- Win and draw detection.
- Heuristic evaluation of the board state.
- Minimax algorithm with Alpha-Beta pruning.
- Control of the main game loop and Pygame events.

## 🛠 How to Use the Repository

📥 1. Clone the repository with Git:

```bash
git clone https://github.com/jimmykiedis/TicTacToeAB.git
cd TicTacToeAB
```

Alternatively, download the project as a ZIP file from the repository page and extract it into a local folder.

📋 2. Prerequisites

- Python 3.x installed.
- Pygame library.

🔗 3. Install the dependency:

```bash
pip install pygame
```

▶️ 4. Run the game

In the project directory, run:

```bash
python main.py
```

Click on an empty cell to make your move with `X`. The AI will make the next move with `O`. To end the match, press `ESC` or close the game window.

## 🏗️ Implementation Strategy

The board is kept in a structure that represents the nine positions of the game. After each human move, the AI evaluates the available possibilities using Minimax. Alpha-Beta pruning stops the analysis of branches that cannot change the final decision, reducing processing cost.

The heuristic function assigns values to favorable or unfavorable states, taking into account possible wins, threats, and opportunities. The search depth is limited to 3 to balance performance and decision quality.

## 🚧 Current Implementation

The project already offers a fully functional human-vs-AI match, a graphical interface, result validation, and move selection by the AI. The improvements listed below have not yet been incorporated.

## 🛠️ Technologies

| Technology | Use in the project |
| --- | --- |
| Python 3.x | Main language |
| Pygame | Graphical window, events, and board rendering |
| Minimax | Search for the best move for the AI |
| Alpha-Beta Pruning | Optimization of the Minimax search |

## 📁 Project Structure

```text
TicTacToeAB/
├── main.py          # Main code, interface, and game logic
└── README.md        # Project documentation
```

## 📝 Final Notes

- The human player uses `X`; the AI uses `O`.
- The AI responds to the human player's moves.
- The depth limitation prioritizes a smooth experience during the match.
- The project is intended for study and experimentation with artificial intelligence in games.

## ⏳ Future Improvements

- Add a scoreboard for wins, losses, and draws.
- Allow selection of difficulty levels.
- Create a match mode between two AIs.
- Include a button to restart the match.
- Add a `requirements.txt` file to make dependency installation easier.

## 📄 License

Educational project developed for studies in Artificial Intelligence.

The code may be consulted, studied, and adapted for educational purposes. To establish clear reuse rules, it is recommended to add a `LICENSE` file with the chosen license.

---

Developed by [@jimmykiedis](https://github.com/jimmykiedis).
