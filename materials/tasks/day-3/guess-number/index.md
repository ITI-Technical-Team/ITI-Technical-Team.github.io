---
title: Guess Number Type
---

# Guess Number Type

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir guess-number` to create a folder called `guess-number`
- write `cd guess-number` to go to the `guess-number` folder
- write `code guess-number.cpp` to create a file called `guess-number.cpp` and open it in the editor

## Problem
Implement a program that takes a **Guess character** (representing a number's sign) and a **number** (an integer), and determines if the guess is correct or not.

The Guess character can be:
* `'P'` for positive numbers (\\(> 0\\))
* `'N'` for negative numbers (\\(< 0\\))
* `'Z'` for zero (\\(= 0\\))

Print `YES` if the guess is correct, and `NO` otherwise.

## Example

**Input:**
```
P
5
```

**Output:**
```
YES
```

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make guess-number
./guess-number
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/3/guess-number
```

## Submit Your Code
Make sure you are in the `guess-number` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/3/guess-number
```
