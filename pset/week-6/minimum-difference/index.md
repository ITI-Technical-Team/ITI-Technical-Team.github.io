---
title: Minimum Difference
---

# B. Find Minimum Absolute Difference

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir minimum-difference` to create a folder called `minimum-difference`
- write `cd minimum-difference` to go to the `minimum-difference` folder
- write `code minimum-difference.cpp` to create a file called `minimum-difference.cpp` and open it in the editor

## Problem

You are given an array of \\(n\\) integers. Your task is to find the **minimum absolute difference** between any two elements in the array.

## Input

The first line contains a single integer \\(n\\) (\\(2 \\leq n \\leq 10^3\\)) — the number of elements in the array.

The second line contains \\(n\\) integers \\(a_1, a_2, \dots, a_n\\) (\\(-10^9 \\leq a_i \\leq 10^9\\)) — the elements of the array.

## Output

Print one integer: **the minimum absolute difference**

## Examples

**Example 1:**

**Input:**

```text
6
1 5 3 19 18 25
```

**Output:**

```text
1
```

**Example 2:**

**Input:**

```text
5
4 9 1 32 13
```

**Output:**

```text
3
```

## Note

- In the first example.

- The minimum absolute difference is 1 (between 18 and 19).

- The output is 1.

- In the second example.

- The minimum absolute difference is 4 (between 9 and 13).

- The output is 4.

## Test Your Code

Make sure you are in the `minimum-difference` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/6/minimum-difference
```

## Submit Your Code

Make sure you are in the `minimum-difference` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/6/minimum-difference
```
