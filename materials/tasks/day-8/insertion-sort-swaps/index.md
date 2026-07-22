---
title: Count Insertion Sort Swaps
---

# Count Insertion Sort Swaps

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir insertion-sort-swaps` to create a folder called `insertion-sort-swaps`
- write `cd insertion-sort-swaps` to go to the `insertion-sort-swaps` folder
- write `code insertion-sort-swaps.cpp` to create a file called `insertion-sort-swaps.cpp` and open it in the editor

## Problem
Write a program that reads an array of integers from the user, sorts it using the **Insertion Sort** algorithm, and returns the total number of swaps (shifts/moves) performed during sorting. The sorting and swap-counting logic must be implemented inside a custom function with the following signature:
`int insertionSortSwaps(int arr[], int n)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `insertionSortSwaps` function to sort the array and get the swap count.
4. Print the total swap count to standard output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./insertion-sort-swaps
<b>5</b>
<b>2 1 3 1 2</b>
4</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make insertion-sort-swaps
./insertion-sort-swaps
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/8/insertion-sort-swaps
```

## Submit Your Code
Make sure you are in the `insertion-sort-swaps` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/8/insertion-sort-swaps
```
