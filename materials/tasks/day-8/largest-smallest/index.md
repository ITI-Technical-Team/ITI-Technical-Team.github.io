---
title: Find Largest and Smallest Element
---

# Find Largest and Smallest Element

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir largest-smallest` to create a folder called `largest-smallest`
- write `cd largest-smallest` to go to the `largest-smallest` folder
- write `code largest-smallest.cpp` to create a file called `largest-smallest.cpp` and open it in the editor

## Problem
Write a program that reads an array of integers from the user, and finds and prints the largest and smallest elements. The finding and printing logic must be implemented inside a custom function with the following signature:
`void FindLargetAndSmallest(int arr[], int n)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `FindLargetAndSmallest` function to find and print the largest and smallest elements.
4. Print the largest and smallest elements to standard output in the exact format shown below.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./largest-smallest
<b>5</b>
<b>2 1 3 1 2</b>
Largest: 3
Smallest: 1</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make largest-smallest
./largest-smallest
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/8/largest-smallest
```

## Submit Your Code
Make sure you are in the `largest-smallest` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/8/largest-smallest
```
