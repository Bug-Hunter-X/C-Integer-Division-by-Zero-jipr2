# C Integer Division by Zero
This repository demonstrates a common runtime error in C: division by zero. The `bug.c` file contains a program that attempts to divide an integer by zero, resulting in undefined behavior. The `bugSolution.c` file provides a solution that addresses this issue.

## Bug
The `bug.c` file contains a simple C program that attempts to divide 10 by 0. This will result in a runtime error, usually a segmentation fault or other unexpected behavior.

## Solution
The `bugSolution.c` file addresses the issue by checking if the divisor is zero before performing the division. If the divisor is zero, it handles the situation gracefully, such as printing an error message or returning a special value.