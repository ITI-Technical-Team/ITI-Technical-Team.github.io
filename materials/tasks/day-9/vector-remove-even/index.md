---
title: Remove Even Numbers (Vector)
---

# Remove Even Numbers (Vector)

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir vector-remove-even` to create a folder called `vector-remove-even`
- write `cd vector-remove-even` to go to the `vector-remove-even` folder
- write `code vector-remove-even.cpp` to create a file called `vector-remove-even.cpp` and open it in the editor

## Problem
Write a program that reads an array/list of integers from the user into a `std::vector`, and removes all even numbers from it. The removal logic must be implemented inside a custom function with the following signature:
`void removeEven(vector<int>& vec)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `removeEven` function to remove even numbers from the vector in-place.
4. Print the remaining odd numbers, space-separated, to standard output. If the vector is empty after removal, print a blank line.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./vector-remove-even
<b>6</b>
<b>1 2 3 4 5 6</b>
1 3 5</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make vector-remove-even
./vector-remove-even
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/9/vector-remove-even
```

## Submit Your Code
Make sure you are in the `vector-remove-even` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/9/vector-remove-even
```
