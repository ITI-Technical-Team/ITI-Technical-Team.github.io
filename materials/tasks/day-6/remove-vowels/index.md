---
title: Remove Vowels
---

# Remove Vowels

## Objective
Write a C++ program that erases all vowels (a, e, i, o, u, case-insensitive) from a sentence using the `.erase()` method.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir remove-vowels` to create a folder called `remove-vowels`
- write `cd remove-vowels` to go to the `remove-vowels` folder
- write `code remove-vowels.cpp` to create a file called `remove-vowels.cpp` and open it in the editor

## Requirements

Write a C++ program in `remove-vowels.cpp` that:
1. Prompts the user to enter a line of text using `getline`.
2. Erases all English vowels (`a`, `e`, `i`, `o`, `u` and their uppercase equivalents) from the text using the `.erase()` method.
3. Prints the modified sentence: `Result: <modified_text>`.

### Example 1
```text
Enter text: Hello World
Result: Hll Wrld
```

### Example 2
```text
Enter text: AEIOU
Result: 
```

### Example 3
```text
Enter text: rhythm
Result: rhythm
```

---

## How to Test
To test your program manually, compile it using:
```bash
make remove-vowels
./remove-vowels
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/6/remove-vowels
```

## Submit Your Code
Make sure you are in the `remove-vowels` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/6/remove-vowels
```
