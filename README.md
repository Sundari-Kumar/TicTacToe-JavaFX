# Tic Tac Toe - MiniMax Algorithm

This is a Tic Tac Toe game implemented using JavaFX and the MiniMax algorithm. It follows the **Model-View-Controller (MVC)** structure and supports varying board sizes. The AI utilizes MiniMax with **Alpha-Beta Pruning** for optimized decision-making.

## **Game Screenshot**

![Tic Tac Toe](3x3Board.PNG)

## **Features**
- Implemented using **JavaFX** for GUI
- Uses **MiniMax Algorithm** for AI decision-making
- Optimized using **Alpha-Beta Pruning** to improve performance
- Supports different board sizes
- Implements an **improved heuristic function** for better AI performance

## **MiniMax Algorithm**
The **MiniMax algorithm** uses backtracking to recursively determine the best move by evaluating all possible board configurations.

### **MiniMax Basic Implementation**
- Assigns values to each board state:
  - **+10** for AI wins
  - **-10** for player wins
  - **0** for draws
- Explores all possible moves (brute-force approach)
- Time complexity: **O(b^d)** where:
  - **b** = branching factor
  - **d** = depth of search tree

### **MiniMax with Alpha-Beta Pruning**
- **Alpha (α)**: Best value the maximizer (AI) can achieve
- **Beta (β)**: Best value the minimizer (player) can achieve
- Prunes unnecessary branches in the game tree
- Reduces time complexity to **O(sqrt(b^d))**

## **Installation & Usage**

1. **Clone the repository**
   ```sh
   git clone https://github.com/Sundari-Kumar/TicTacToe-JavaFX.git
   cd TicTacToe-JavaFX
   ```
2. **Compile and run the game**
   ```sh
   javac Main.java
   java Main
   ```

## **Resources**
- [Minimax with Alpha Beta Pruning - John Levine](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)
- [MIT OpenCourseWare - Game Search](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)
- [The Coding Train - Tic Tac Toe AI](https://www.youtube.com/watch?v=trKjYdBASyQ)

## **License**
This project is licensed under the **MIT License**.

---

Enjoy playing Tic Tac Toe with an intelligent AI! 🎮🤖
