---
title: Reverse a String (Stack)
---

# Reverse a String (Stack)

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir reverse-string` to create a folder called `reverse-string`
- write `cd reverse-string` to go to the `reverse-string` folder
- write `code reverse-string.cpp` to create a file called `reverse-string.cpp` and open it in the editor

## Problem
Write a program that uses `std::stack` to reverse a given string.

The program should:
1. Read a string from standard input (supporting lines with spaces).
2. Push all the characters of the string onto a stack.
3. Pop characters from the stack one by one to reconstruct the string in reverse.
4. Print the reversed string to standard output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./reverse-string
<b>hello world</b>
dlrow olleh</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make reverse-string
./reverse-string
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/9/reverse-string
```

## Submit Your Code
Make sure you are in the `reverse-string` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/9/reverse-string
```
