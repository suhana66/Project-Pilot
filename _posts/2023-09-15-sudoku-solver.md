---
title: Sudoku Solver GUI
category: Project Guidelines
level: 1
---

## Overview
In this project, you will create a user-friendly graphical interface for playing Sudoku. Sudoku is a 9x9 grid puzzle where each column, row, and 3x3 subgrid must contain all digits from 1 to 9 without repetition. Users can generate random Sudoku puzzles, get instant solutions, and input their own values for validation.

## Objective
The objective of this project is to help you learn to develop a GUI using a programming framework or library like Tkinter, PyQt, JavaFX. You will also improve upon your knowledge of event-driven programming, while applying OOP concepts.

## Deliverables
At the end of this project, you will have:

1. Source code for a fully functional Sudoku Solver, with documentation (as needed).
2. A README.md file with instructions on how to run and use the application.

## Covered Concepts
- GUI design and development
- Sudoku puzzle generation algorithms
- Sudoku puzzle solving algorithms
- User interface components
- Event-driven programming for user interactions
- Error handling and input validation
- Code modularity and organization

## Requirements

### Puzzle Algorithms
- Implement Sudoku puzzle generation algorithms to create solvable puzzles.
- Ensure generated puzzles have a unique solution.
- Users should be able to fill in squares with valid digits (1-9) on the unsolved Sudoku board.
- Ensure the program validates user input for correctness and indicates if the input is invalid.
- Implement an algorithm to solve the randomly generated sudoku board.

### GUI Design
- Include a clear display of the Sudoku grid in the application.
- Provide a "Clear" button to clear all user inputs and start over the game with the same board.
- Provide a "Solve" button to display the unique solution to the board.
- Provide a "Reset" button to generate a completely new puzzle.
- Handle button clicks, mouse events, and keyboard inputs for GUI components.
- Include visual indicators for the validity of user input.

### Code Organization and Modularity
- Organize your code into well-defined modules and classes.
- Use appropriate object-oriented programming (OOP) principles for code organization.
- Include comments and documentation to explain the code's functionality.
- Create a detailed README.md with setup instructions, project overview, user prerequisites and functional demonstrations (screenshots/GIFs) if possible.

## Optional Enhancements
- Implement an algorithm to rate the difficulty of generated puzzles and offer the rating to users.
- Add a timer to track how long it takes the user to solve a puzzle.
- Extend the application to support different sudoku grid sizes, such as 6x6 or 16x16 puzzles.
- Implement a multiplayer feature that allows two users to play on the same puzzle simultaneously.
- Implement a hint feature that allows users to access the solution to one square in the board a specified number of times.
- Implement a strike system that penalizes users with strikes for incorrect inputs, enhancing the challenge and encouraging careful digit entry.