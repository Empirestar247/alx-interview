# 0x07-rotate_2d_matrix

## Description
This project focuses on manipulating a two-dimensional matrix (2D matrix) using Python, specifically rotating the matrix 90 degrees clockwise without using additional memory for matrix storage. The rotation is done entirely in-place to ensure space complexity is minimized.

## Objective
To implement a function that takes an n x n matrix and rotates it 90 degrees clockwise in-place, demonstrating a grasp of matrix operations and data manipulation in Python.

## Requirements
Language: Python 3.8.10
System: Ubuntu 20.04 LTS
Editors: vi, vim, emacs
Code must follow Pycodestyle (version 2.8.0)
No external modules are to be imported
Each file must be executable and start with #!/usr/bin/python3
Installation
To run the scripts, clone the repository and navigate to the project directory:


git clone <repository_url>
cd alx-interview/0x07-rotate_2d_matrix

Usage
Execute the Python scripts to rotate a given matrix:


./main_0.py
This script uses the rotate_2d_matrix(matrix) function to perform the rotation and prints the matrix after rotation.

Files
0-rotate_2d_matrix.py - Contains the implementation of the function rotate_2d_matrix(matrix) which rotates the matrix in-place.
main_0.py - Test script that imports and tests the function from 0-rotate_2d_matrix.py.
Example
Input:


1 2 3
4 5 6
7 8 9
Output after rotation:


7 4 1
8 5 2
9 6 3



