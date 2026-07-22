---
title: Determine if Array is Sorted
---

# Determine if Array is Sorted

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir is-sorted` to create a folder called `is-sorted`
- write `cd is-sorted` to go to the `is-sorted` folder
- write `code is-sorted.cpp` to create a file called `is-sorted.cpp` and open it in the editor

## Problem
Write a program that reads an array of integers from the user and determines if the array is sorted in ascending (non-decreasing) order. The sorting verification logic must be implemented inside a custom function with the following signature:
`bool isSorted(int arr[], int n)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `isSorted` function to determine if the array is sorted.
4. Print `Yes` if the array is sorted, or `No` if it is not.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

### Unsorted Case:
<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./is-sorted
<b>5</b>
<b>2 1 3 1 2</b>
No</code></pre></div></div>

### Sorted Case:
<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./is-sorted
<b>5</b>
<b>1 2 3 4 5</b>
Yes</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make is-sorted
./is-sorted
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/8/is-sorted
```

## Submit Your Code
Make sure you are in the `is-sorted` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/8/is-sorted
```
