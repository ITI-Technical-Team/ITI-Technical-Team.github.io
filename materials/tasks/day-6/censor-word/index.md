---
title: Censor Word
---

# Censor Word

## Objective
Write a C++ program that replaces all occurrences of a target word in a sentence with a replacement word.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir censor-word` to create a folder called `censor-word`
- write `cd censor-word` to go to the `censor-word` folder
- write `code censor-word.cpp` to create a file called `censor-word.cpp` and open it in the editor

## Requirements

Write a C++ program in `censor-word.cpp` that:
1. Prompts the user to enter a line of text using `getline`.
2. Prompts the user to enter a target word to find.
3. Prompts the user to enter a replacement word.
4. Finds and replaces all occurrences of the target word in the text with the replacement word using `.find()` and `.replace()` in a loop.
5. Prints the modified sentence: `Result: <modified_text>`.

### Example
```text
Enter text: I love bad food and bad drinks
Enter target: bad
Enter replacement: good
Result: I love good food and good drinks
```

---

## How to Test
To test your program manually, compile it using:
```bash
make censor-word
./censor-word
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/6/censor-word
```

## Submit Your Code
Make sure you are in the `censor-word` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/6/censor-word
```
