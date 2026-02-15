\# Snail Matrix Traversal



\## Description

Given a square matrix (n × n), return all elements arranged in clockwise spiral order, starting from the top-left corner and moving inward layer by layer.


The matrix must:

- Be initially empty
- Be filled dynamically using an algorithm
- Not be hardcoded
- Be printed in matrix format (not as a single line list)

---

## Approach

1. Create an empty matrix of size n × n.
2. Use four boundaries:
   - top
   - bottom
   - left
   - right
3. Fill numbers from 1 to n² in spiral order:
   - Left → Right
   - Top → Bottom
   - Right → Left
   - Bottom → Top
4. Move the boundaries inward after each layer.
5. Print the matrix row by row.


\## How to Run



Make sure Python 3 is installed.



Run:



python solution.py



