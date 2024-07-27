# Sudoku GUI

## Overview

The Sudoku GUI is a Python application built using Tkinter, designed to create and solve Sudoku puzzles. The application allows users to select puzzle difficulty levels, choose from different puzzles, and solve them using two algorithms: Backtracking and Arc-3. It also features a timer to track the solving duration.

## Features

- **Sudoku Grid**: Displays a 9x9 Sudoku grid with customizable colors and styling.
- **Difficulty Levels**: Choose between Easy, Medium, and Hard levels to generate puzzles with varying numbers of pre-filled cells.
- **Puzzle Selection**: Select from predefined puzzles (Puzzle 1, Puzzle 2, Puzzle 3, Puzzle 4).
- **Solve Algorithms**: Solve the puzzle using either Backtracking or Arc-3 algorithms.
- **Timer**: Displays the time taken to solve the puzzle.
- **Highlight Conflicts**: Highlights cells with conflicts if the puzzle has no solution.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/sudoku-gui.git

Navigate to the Project Directory:

bash

    cd sudoku-gui

  Install Dependencies:
  Ensure you have Python 3.x installed. The required packages are tkinter, which is included with the standard Python installation.

Usage

Run the Application:

  bash

    python sudoku_gui.py

Interface Overview:

  Sudoku Grid: A 9x9 grid where users can input numbers.
  Level Selection: Choose the difficulty level of the puzzle.
  Puzzle Selection: Select a puzzle from the options provided.
  Solve Buttons: Solve the puzzle using Backtracking or Arc-3 algorithms.
  Reset Button: Resets the puzzle and generates a new one based on the selected difficulty.
  Timer: Displays the time taken to solve the puzzle.
