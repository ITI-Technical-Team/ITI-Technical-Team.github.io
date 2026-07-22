---
title: Find First Occurrence
---

# Find First Occurrence

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir first-occurrence` to create a folder called `first-occurrence`
- write `cd first-occurrence` to go to the `first-occurrence` folder
- write `code first-occurrence.cpp` to create a file called `first-occurrence.cpp` and open it in the editor

## Problem
Write a program that reads a sorted array of integers and finds the index of the first occurrence of a target integer using **Binary Search**. The binary search logic must be implemented inside a custom function with the following signature:
`int findFirstOccurrence(int arr[], int size, int target)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read `N` sorted integers from standard input.
3. Read the target integer `x` to search for.
4. Call the `findFirstOccurrence` function to get the first index where `x` occurs (or `-1` if it is not found).
5. Print the resulting index (or `-1`) to standard output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./first-occurrence
<b>5</b>
<b>1 7 7 15 20</b>
<b>7</b>
1</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make first-occurrence
./first-occurrence
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/7/first-occurrence
```

## Submit Your Code
Make sure you are in the `first-occurrence` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/7/first-occurrence
```
