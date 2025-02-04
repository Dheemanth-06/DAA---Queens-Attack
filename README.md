# Queen's Attack

## Overview
This program calculates the number of squares a queen can attack on an `n x n` chessboard, given its position and the locations of obstacles.

## Features
- Computes the maximum attackable squares in all 8 directions.
- Considers obstacles that may block the queen's movement.
- Efficiently processes input using standard I/O.

## Requirements
- C++ compiler (GCC recommended)
- Standard Template Library (STL)

## Compilation
To compile the program, run:
```sh
 g++ queens_attack.cpp -o queens_attack
```

## Usage
Run the program with:
```sh
 ./queens_attack
```

## Input Format
The input consists of:
1. An integer `n` representing the board size.
2. An integer `k` representing the number of obstacles.
3. Two integers `r_q` and `c_q` for the queen's position.
4. `k` pairs of integers, each representing the row and column of an obstacle.

### Example Input
```
5 3
4 3
5 5
4 2
2 3
```

### Example Output
```
10
```

## Explanation
Given a `5x5` board with the queen at (4,3) and obstacles at (5,5), (4,2), and (2,3), the program computes the attackable squares and outputs `10`.

## License
This project is licensed under the MIT License.
