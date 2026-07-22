---
title: Find Smallest Element Greater Than
---

# Find Smallest Element Greater Than

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir smallest-greater` to create a folder called `smallest-greater`
- write `cd smallest-greater` to go to the `smallest-greater` folder
- write `code smallest-greater.cpp` to create a file called `smallest-greater.cpp` and open it in the editor

## Problem
Write a program that reads a sorted array of integers and finds the index of the smallest element that is strictly greater than a given integer `x` using **Binary Search**. The logic must be implemented inside a custom function with the following signature:
`int findSmallestElementGreaterThan(int arr[], int size, int target)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read `N` sorted integers from standard input.
3. Read the integer `x`.
4. Call the `findSmallestElementGreaterThan` function to get the index of the smallest element strictly greater than `x` (or `-1` if no such element exists).
5. Print the resulting index (or `-1`) to standard output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

```text
$ ./smallest-greater
**5**
**1 7 7 10 15**
**7**
3
```

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make smallest-greater
./smallest-greater
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/7/smallest-greater
```

## Submit Your Code
Make sure you are in the `smallest-greater` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/7/smallest-greater
```
