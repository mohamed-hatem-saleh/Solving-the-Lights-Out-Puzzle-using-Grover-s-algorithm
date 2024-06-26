# Solving the Lights Out Puzzle Using Grover's Algorithm

## Overview

This project demonstrates the solution of the Lights Out Puzzle using Grover's Algorithm in Quantum Computing. The project was developed as part of the course CIE470: Introduction to Quantum Information and Computation.

## Problem Description

The Lights Out Puzzle consists of an NxN grid of bulbs, where each bulb occupies a cell on the grid and has its own switch. Pressing a switch toggles the state of the bulb between "on" and "off," as well as the states of the vertically and horizontally adjacent bulbs. The objective is to determine the sequence of switch presses that turns off all the lights on the grid.

In this project, we solve the puzzle for a 3x3 grid with the initial state:

\[ \text{[0, 1, 1, 0, 0, 1, 1, 0, 0]} \]

Here, "0" represents a bulb that is off, and "1" represents a bulb that is on.

## Contents

- **Quantum Circuit Initialization:** Setting up the quantum and classical registers.
- **Function Definitions:** 
  - Mapping the indices of the vector into a matrix.
  - Identifying the neighbors affected by a switch.
- **Algorithm Implementation:** Detailed steps to apply Grover's Algorithm to the problem.

## Getting Started

### Prerequisites

To run the code in this project, you need the following packages:
- Qiskit
- NumPy

You can install the required packages using pip:

```bash
pip install qiskit numpy
```

### Running the Notebook

1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <repository_directory>
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Project_notebook.ipynb
    ```

4. Run the cells in the notebook to see the implementation and results.

## Project Structure

- `Project_notebook.ipynb`: The main Jupyter Notebook containing the project code and documentation.
- **Quantum Circuit Initialization**: Initializing the quantum and classical registers required for the algorithm.
- **Function Definitions**: 
  - `initialize_square_matrix(N)`: Maps the indices of the vector into a matrix.
  - `get_neighbors(row, col, matrix)`: Returns the neighbors affected while switching.
- **Algorithm Implementation**: Applying Grover's Algorithm to find the solution to the Lights Out Puzzle.

## Authors

- Mohamed Hatem Saleh
