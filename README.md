# RecurrunceWith3Methods

This program implements the following piecewise recurrence relation in C using three different approaches: recursive, dynamic programming, and iterative.

## Pros & Cons of each

### 1 Recursive Approach

#### Pros:
- Simple and easy to read.

#### Cons:
- Exponential time complexity O(2^n), very slow at large values of n.
- High memory usage due to duplicate recursive calls, for example f(1) will be called more than 60 if n is equal to 70.

### 2 Dynamic Programming Approach

#### Pros:
- Efficient and faster than the recursive approach for large values of n O(n).
- Avoids redundant calculations (as in the recursive approach) by storing previously calculated values.


#### Cons:
- Requires additional memory to store the array of previously calculated values.
- Implementation is more complex compared to the recursive approach.

### 3 Iterative Approach

#### Pros:
- Efficient and faster than both the recursive.
- Very easy to read.
- Linear time complexity.

#### Cons:



## Development Environment

- Operating System: Windows 10
- Compiler: GCC


## Compilation

To compile the source code, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where the source code is located.
3. Run the following command:
 
```bash
gcc Q2.c -o Q2

```

4. The program will execute and display the same number but with 3 approaches for the specified input value (n).

 - Change the value of n in main() to get different output.


