# Dangling Pointer Bug in C

This repository demonstrates a common error in C programming: using a dangling pointer. A dangling pointer points to memory that has been freed or is no longer valid. Accessing a dangling pointer can lead to unpredictable behavior and program crashes. 

The `bug.c` file contains code that demonstrates this issue.  The `bugSolution.c` file provides a corrected version.

## How to Reproduce

1. Clone this repository.
2. Compile `bug.c` using a C compiler (like GCC): `gcc bug.c -o bug`
3. Run the executable: `./bug`

You might observe unexpected behavior or a program crash.

## Solution

The solution in `bugSolution.c` addresses the issue by carefully managing memory allocation and pointer usage.