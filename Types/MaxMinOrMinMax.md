# Overview
The question always mention "find the minimum of a maximum value" or "minimize a maximum value". An array `arr` and a number `k` will be given.

Two algorithm need to be used to solve this question, one is "greedy" algorithm in a "check" function, another is "binary search" algorithm where the check function is used to distinguish the "middle" value and move "left" or "right" pointer. The "check" function takes `x` to see if `x` could satisfy `k` and return a boolean value.

So, there are some characteristics:
1. The value `k` need to be used in the "check" function.
2. The value `x` will be the final answer after the binary search.


This question involves descriptions of "finding the minimum of a maximum value" or "minimizing a maximum value." You will be provided with an array `arr` and a number `k`.

To address this problem, two distinct algorithms are required:

1. A "Check" Function:
    - Implement a "check" function using the greedy algorithm or other algorithm.
    - The function should take the parameter `x` and evaluate whether `x` satisfies the condition `k`.
    - Return a boolean value indicating the result of the check.
2. Binary Search Algorithm:
    - Utilize the binary search algorithm, where the "check" function helps determine the appropriate action (move "left" or "right" pointer) based on a "middle" value.
    - The "check" function should incorporate the value `k` in its evaluation.
    - The final answer, denoted as `x`, will be obtained through the binary search.

Key Characteristics:
1. Ensure that the value `k` is integrated into the "check" function.
2. The variable `x` represents the ultimate solution, determined through the binary search.