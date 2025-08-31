# Connecet-4-Using-Minimax-Algorithm
A Connect 4 game with an AI opponent using the Minimax algorithm and Alpha-Beta pruning. Built with Python and Pygame, it supports interactive gameplay, AI difficulty levels, real-time win detection, and an optimized decision-making system for challenging matches


---

## Table of Contents
- [Overview](#Overview)
- [Features](#Features)
- [Project Structure](#Project Structure)
- [Methodology](#methodology)
- [Results](#Results)
- [License](#License)

---

## Overview
This project implements the classic **Connect 4** game with an AI opponent that uses the **Minimax algorithm with Alpha-Beta pruning** to make optimal moves. 
The game board is visualized using `pygame`, allowing a smooth and interactive experience. 

---

## 🎮 Features
- **2D game board** built with `pygame`.
- **Player vs AI gameplay** with three difficulty levels: Easy, Medium, and Hard.
- **AI Decision-making** powered by Minimax with Alpha-Beta pruning for efficient move selection.
- **Game logic** includes piece placement, win detection (horizontal, vertical, diagonal), and turn management.
- Interactive **GUI** with real-time updates and winner announcements.

---

## Project Structure

### 1. Board Creation
- Built using `pygame`.
- Functions:
  - `create_board()`: Initializes the board.
  - `draw_board()`: Displays the board on the screen.

### 2. Game Settings
Functions for game mechanics:
- `drop_piece`: Places a piece (player or AI) in a column.
- `is_valid_location`: Checks if a column has space.
- `get_next_open_row`: Finds the next empty row in a column.
- `winning_move`: Checks if there is a winning combination.

### 3. AI Player
- Easy: Random column selection.
- Medium: Uses `pick_best_move` heuristic.
- Hard: Uses **Minimax with Alpha-Beta pruning** for optimal moves.
- Handles AI turns, move validation, win detection, and board updates.

### 4. Alpha-Beta Pruning
- Optimized Minimax algorithm to prune unnecessary branches and reduce computation time.
- Parameters include board state, alpha, beta, and player type.

### 5. Game Loop
- Controlled by a `while` loop.
- Handles player/AI moves, GUI updates, mouse interactions, and game termination.

---

## 🎮 Example Gameplay
- Player clicks a column to drop a piece.
- AI responds with the best move based on selected difficulty.
- Game announces the winner once four connected pieces are found.

---

## Results
| Feature                | Description                             |
|------------------------|-----------------------------------------|
| AI Difficulty Levels   | Easy, Medium, Hard                      |
| AI Algorithm           | Minimax with Alpha-Beta pruning         |
| GUI                    | Built with `pygame`                     |
| Game Logic             | Full rule enforcement & win detection   |
| Performance            | Optimized for smooth gameplay           |

---

## License
This project is for **showcasing purposes only**. All rights reserved.
