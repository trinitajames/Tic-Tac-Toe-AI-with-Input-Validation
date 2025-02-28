# Tic-Tac-Toe-AI-with-Input-Validation

An **unbeatable Tic-Tac-Toe game** built using Python and the **Minimax algorithm**. The AI **never loses** and always chooses the best possible move. The project also includes **input validation** to ensure smooth gameplay.

## 🚀 Project Overview

This project implements a **command-line Tic-Tac-Toe game** where:
- **The human player ("X") competes against an AI ("O").**
- **The AI uses the Minimax Algorithm**, making it **unbeatable**.
- **Input validation** ensures that:
  - Users enter valid row/column values.
  - Moves are not placed on already occupied cells.
  - The game does not crash due to incorrect input.

## 🏆 Game Logic & AI Strategy

### 🎯 **1. Game Rules**
- The game is played on a **3x3 grid**.
- Players take turns marking a space with **"X" (human) or "O" (AI)**.
- The first player to align **three marks in a row, column, or diagonal** wins.
- If the board is full and no player has won, it results in a **tie**.

---

## 🤖 **Minimax Algorithm - The Brain Behind the AI**
The **Minimax algorithm** is a decision-making algorithm used in two-player games like Tic-Tac-Toe. The AI assumes:
1. **The AI (O) plays optimally to maximize its chance of winning.**
2. **The human (X) also plays optimally, trying to minimize the AI’s advantage.**
3. **The AI explores all possible future moves and selects the best one.**

---

## 📌 **How the Minimax Algorithm Works**
### 🔍 **Step-by-Step Process**
1. **Simulate all possible game states.**  
   - The AI looks ahead at every potential move.
   
2. **Assign a score to each outcome.**  
   - AI **wins** → Score = **+10**  
   - Human **wins** → Score = **-10**  
   - Tie → Score = **0**

3. **Minimizing and Maximizing Turns**  
   - **AI's turn (Maximizer)**: It selects the move that leads to the **highest** possible score.
   - **Human's turn (Minimizer)**: It selects the move that leads to the **lowest** possible score.

4. **Recursively evaluate all possible moves** until the AI finds the **best** one.

---

## 🏗 **Minimax Decision Tree Example**
              (AI's Turn)
                 |
    --------------------------------
    |                              |
(Human Move)                 (Human Move)
 -10 (Loss)                     0 (Tie)


- AI **chooses the move that prevents a loss** and **maximizes its chance of winning**.

---

## 🔹 **Game Flow**
1. **User enters a move (row & column).**
2. **AI evaluates the board** and selects the best move.
3. **Board updates**, and the game continues until there is a **winner or tie**.
4. **Game announces the winner** or declares a tie.

---

## 🎯 **Why is the AI Unbeatable?**
- The AI **never makes mistakes** because it **explores all possible game outcomes**.
- It can **force a draw if the human plays optimally**.
- If the human makes a mistake, the AI **takes advantage and wins**.

---

## 🔥 **Future Improvements**
- **Optimize AI** with **Alpha-Beta Pruning** for faster decisions.
- **GUI Version** using Tkinter or Pygame.
- **Multiplayer Mode** (Human vs. Human).

---

## 📜 License
This project is open-source and free to use under the MIT License.

---
