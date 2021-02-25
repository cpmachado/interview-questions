# Queens problem

Have you watched *Queen's Gambit* or you know chess?

If the answer is negative about the second, please reconsider life choices.

Do you know the 8 Queens puzzle?

Required knowledge to solve:
- What is a chess board?
  + It's an 8x8 squares board.
  + It has eight squares length in either side.
  + These are mapped from a-h, 1-8.
- How the queen moves?
  + It moves any number of squares in either row or column.
  + It moves in any diagonal.
- What is a piece attacking the other?
    + It is simple as a piece can move into the square of another piece

*Reference: <https://en.wikipedia.org/wiki/Eight_queens_puzzle>*

## Description

Let us write a function called *queens*.

Parameters:
- n: a positive number, which is the size of the side of a board

Here is the header of the function
```javascript
    function queens(n) {
        // your code here
    }
```

### Functionality

- Return number of solutions, in n by n board, with n queens.
- Bonus material, return list in algebraic notation.(a-h, 1-8)

### Example

Sample call, in javascript:

```javascript
    queens(1); // 1
    queens(2); // 0
    queens(3); // 0
    queens(4); // 2
    queens(5); // 10
    queens(6); // 4
    queens(7); // 40
    queens(8); // 92
```