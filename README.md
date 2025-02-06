# Unexpected Pointer Behavior in C

This repository demonstrates a simple C program that showcases how incorrect use of pointers can lead to unexpected behavior. The code initializes an integer variable and modifies its value indirectly using a pointer. 

## Bug

The `bug.c` file contains the code with the potential issue.  The core problem lies in the way the pointer modifies the value. While this might appear straightforward, there's a subtlety that can cause problems in more complex scenarios. 

## Solution

The `bugSolution.c` file provides a corrected version of the code, demonstrating best practices for using pointers. It highlights how to avoid potential pitfalls and ensures the expected behavior.

## How to Run

1. Clone this repository.
2. Compile the code: `gcc bug.c -o bug` and `gcc bugSolution.c -o bugSolution`
3. Run the executables: `./bug` and `./bugSolution`

Compare the outputs to understand the difference between the buggy and corrected versions.