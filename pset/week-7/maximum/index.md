---
title: Maximum
---

# B. Max

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir maximum` to create a folder called `maximum`
- write `cd maximum` to go to the `maximum` folder
- write `code maximum.cpp` to create a file called `maximum.cpp` and open it in the editor

## Problem

Given an array \\(n\\), you have to find the maximum number of the array and determine how many numbers in the array that the maximum number is divisible by it.

## Input

First line contains a number \\(n (1 \\leq n \\leq 10^4)\\), the size of the array.

Second line contains \\(n\\) numbers \\(a_i (1 \\leq a_i \\leq 10^5)\\), the elements of the array.

## Output

Print a single number representing the number of numbers that the maximum number of the array is divisible by them.

## Examples

**Example 1:**

**Input:**

```text
7
3 2 4 1 10 6 8
```

**Output:**

```text
3
```

**Example 2:**

**Input:**

```text
3
2 4 11
```

**Output:**

```text
1
```

## Note

For the first example: The maximum number of the array is 10, and it's divisible by 10, 2 and 1 in this array.

## Test Your Code

Make sure you are in the `maximum` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/7/maximum
```

## Submit Your Code

Make sure you are in the `maximum` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/7/maximum
```
