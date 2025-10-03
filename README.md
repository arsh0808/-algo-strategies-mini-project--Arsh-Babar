# -algo-strategies-mini-project--Arsh-Babar
Lab Assignment-2
# Algorithm Strategies Mini Project (Problems 1-4)

This repository contains a collection of classic algorithmic problems implemented in Python with simple visualizations, designed as a mini project for educational purposes. The entire project is intended to run in a single Jupyter notebook or Google Colab cell, covering four algorithmic problems commonly encountered in interviews and algorithm courses.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Problems Implemented](#problems-implemented)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Code Structure](#code-structure)
- [Notes](#notes)
- [License](#license)

---

## Project Overview

This project demonstrates fundamental algorithmic techniques using Python, including:

- **Greedy algorithms**
- **Dynamic Programming (DP)**
- **Backtracking**
- **Naive brute-force search**

Each problem comes with a brief explanation, an implementation, example input, output printing, and visualization plots.

---

## Problems Implemented

### Problem 1: Scheduling TV Commercials (Greedy Job Sequencing)

- **Goal:** Maximize total profit by scheduling ads before their deadlines.
- **Approach:** Sort ads by profit descending, assign each ad to the latest available slot before its deadline.
- **Complexity:** O(n log n) due to sorting, with scheduling complexity O(n * D), where D is the max deadline.
- **Visualization:** Cumulative revenue as more ads are chosen.

### Problem 2: 0/1 Knapsack Problem (Dynamic Programming)

- **Goal:** Maximize profit without exceeding capacity constraints.
- **Approach:** Bottom-up DP table filling with backtracking to find chosen items.
- **Complexity:** O(n * capacity) time and space.
- **Visualization:** Max profit vs budget (capacity).

### Problem 3: Sudoku Solver (Backtracking)

- **Goal:** Solve a 9x9 Sudoku puzzle.
- **Approach:** Recursive backtracking with safe checks on rows, columns, and 3x3 boxes.
- **Complexity:** Worst-case exponential.
- **Visualization:** Solve time vs number of empty cells.

### Problem 4: Password Cracking (Naive Brute-Force) - Educational Only

- **Goal:** Demonstrate brute-force search over all candidate passwords.
- **Approach:** Enumerate all possible strings up to a max length from a given charset.
- **Complexity:** O(|charset|^L) exponential.
- **Visualization:** Number of password combinations vs password length (log scale).

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/algo-strategies-mini-project.git
   cd algo-strategies-mini-project
