# sudoku-magic-ai-solvers

This project contains two AI-based puzzle solvers:

## 1. Sudoku Solver (Backtracking Search + Heuristics)
- Solves **classic 9x9 Sudoku** puzzles.
- Implements:
  - **Backtracking Search**
  - **MRV (Minimum Remaining Values)**
  - **Degree Heuristic**
  - **Least Constraining Value**
  - **AC-3 Algorithm** for domain reduction
- Ensures constraints:
  - Each row, column, and 3x3 box contains digits 1–9 without repetition.
- Capable of solving generated or user-provided puzzles.

## 2. Magic Square Solver (Genetic Algorithm)
- Solves **3x3 Moving Magic Square** puzzles where the number 9 is the movable tile.
- Objective: Arrange tiles so each row, column, and diagonal sums to 15.
- Features:
  - **Genetic Algorithm** for solution search
  - Random population generation, selection, crossover, mutation
  - Stops when a valid magic square is found

## Features
- Modular code with clear function separation.
- In-code comments explaining logic.
- Random puzzle generation and solving.
- Handles zero, one, or multiple solutions.
---
