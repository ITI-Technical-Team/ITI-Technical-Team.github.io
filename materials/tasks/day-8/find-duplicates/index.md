---
title: Find Duplicate Elements
---

# Find Duplicate Elements

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir find-duplicates` to create a folder called `find-duplicates`
- write `cd find-duplicates` to go to the `find-duplicates` folder
- write `code find-duplicates.cpp` to create a file called `find-duplicates.cpp` and open it in the editor

## Problem
Write a program that reads an array of integers from the user, and finds and prints all duplicate elements. The duplicate-finding logic must be implemented inside a custom function with the following signature:
`void findDuplicates(int arr[], int n)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `findDuplicates` function to find and print the duplicate elements in **ascending sorted order**, with a single space separating each number.
4. Each duplicate number should be printed **only once**, regardless of how many times it appeared in the original array. If there are no duplicates, output a single newline or empty output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./find-duplicates
<b>8</b>
<b>1 2 3 2 4 3 5 1</b>
1 2 3</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make find-duplicates
./find-duplicates
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/8/find-duplicates
```

## Submit Your Code
Make sure you are in the `find-duplicates` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/8/find-duplicates
```
