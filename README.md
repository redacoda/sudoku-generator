# Sudoku Generator Program

This program is divided into several parts.

## Part 1: Generation

We use Python’s random library to generate a full, valid Sudoku grid, following specific rules to ensure the solution is correct.

## Part 2: Erasing Cells

In this part, we use a "Sudoku solver" program that I created. The idea is to randomly erase one cell at a time and check if the puzzle can still be solved after each removal. This helps ensure that the puzzle remains valid and solvable.

However, there's a limitation: my solver isn't efficient enough to handle very complex puzzles. As a result, I can’t reach the theoretical maximum of 64 erased cells. Right now, I'm limited to about 43. Still, it's a big step for me and a project I’m proud of!
