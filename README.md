# Uncommon C Bug: Integer Overflow Leading to Unexpected Behavior

This repository demonstrates a subtle bug in C related to integer overflow.  The provided code snippet showcases how an integer overflow can lead to unexpected behavior, potentially resulting in program crashes or security vulnerabilities.

The bug is explained in the `bug.c` file along with a solution in `bugSolution.c`.  The solution illustrates a robust approach to handling potential integer overflows.

## Bug Explanation

The original code attempts to manipulate a pointer. While it functions on simple cases, it can cause problems under certain circumstances: Memory corruption or unexpected behavior may occur if the pointer is used incorrectly.  Memory access violations and segmentation faults are common outcomes. 

## Solution

The solution in `bugSolution.c` shows improved code that reduces the risk of issues. Robust error checking, boundary checks, and safe memory management techniques can significantly mitigate the risk of this type of bug.