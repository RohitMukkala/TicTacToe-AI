# **Tic-Tac-Toe AI**

## **Description**

This repository contains an implementation of an AI agent capable of playing the classic game of Tic-Tac-Toe against a human player. The AI agent employs algorithms like Minimax with or without Alpha-Beta Pruning to ensure an unbeatable game experience. This project is designed to provide insights into game theory and basic search algorithms.

### **Key Features**

- **AI Player:** The AI agent is programmed to make optimal moves using the Minimax algorithm, ensuring that it plays the game strategically to achieve victory or a draw.

- **User Interaction:** Players can interact with the game by inputting their moves via the console interface.

- **Game Logic:** The game includes functionalities for checking winning conditions, detecting draws, and managing the game flow.

### **How it Works**

1. **Board Representation:** The Tic-Tac-Toe board is represented using a dictionary data structure, where keys represent board positions and values represent player moves ('X' for the AI, 'O' for the human player, and empty for vacant positions).

2. **AI Decision Making:** The AI agent employs the Minimax algorithm to search through the game tree and determine the best possible move at each turn, considering the opponent's potential moves.

3. **User Input Handling:** Human players input their moves via the console, with the game ensuring the validity of the moves and updating the board accordingly.

### **Getting Started**

1. Clone the repository to your local machine.
2. Ensure Python is installed on your system.
3. Run the `tictactoe.py` file to start playing against the AI.

### **Contributing**

Contributions to the project are welcome! Whether it's optimizing the AI algorithm, improving the user interface, or adding new features, your contributions can enhance the overall gameplay experience. Fork the repository, make your changes, and submit a pull request.


