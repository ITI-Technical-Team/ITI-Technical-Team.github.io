---
title: Find Minimum
---

# Find Minimum

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir find-minimum` to create a folder called `find-minimum`
- write `cd find-minimum` to go to the `find-minimum` folder
- write `code find-minimum.cpp` to create a file called `find-minimum.cpp` and open it in the editor

## Problem
Write a program that reads an array of integers from the user and finds the minimum value in the array. The finding logic must be implemented inside a custom function with the following signature:
`int findMinimum(int arr[], int size)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `findMinimum` function to get the minimum value.
4. Print the minimum value to standard output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

```text
$ ./find-minimum
**5**
**1 7 7 15 10**
1
```

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make find-minimum
./find-minimum
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/7/find-minimum
```

## Submit Your Code
Make sure you are in the `find-minimum` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/7/find-minimum
```
