# MCTS
# Tic-Tac-Toe with MCTS AI
A Python implementation of the classic Tic-Tac-Toe game with a Monte Carlo Tree Search (MCTS) AI opponent.
# Game Description
Tic-Tac-Toe is a simple yet strategic game where two players, X and O, take turns marking a 3x3 grid. The first player to get three in a row (horizontally, vertically, or diagonally) wins the game. If all squares are filled and no player has won, the game is a draw.
# MCTS AI
The MCTS AI uses a tree search algorithm to explore the game tree and select the best move. The algorithm consists of four main steps:

Selection: Select a child node to explore based on the UCB (Upper Confidence Bound) formula.
  Expansion: Expand the selected node by generating a new child node.
  
  Simulation: Simulate a random playout from the new child node to estimate its value.
  
  Backpropagation: Update the value and visit count of the nodes in the path from the new child node to the root.

# Requirements
Python 3.x
NumPy library

# License
This project is licensed under the MIT License. See LICENSE for details.

# Contributing
Contributions are welcome! If you'd like to improve the game or AI, please fork the repository and submit a pull request.
