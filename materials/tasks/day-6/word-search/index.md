---
title: Word Search
---

# Word Search

## Objective
Write a C++ program that reads a line of text and a search word, and finds the index of the first occurrence of the search word.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir word-search` to create a folder called `word-search`
- write `cd word-search` to go to the `word-search` folder
- write `code word-search.cpp` to create a file called `word-search.cpp` and open it in the editor

## Requirements

Write a C++ program in `word-search.cpp` that:
1. Prompts the user to enter a line of text using `getline`.
2. Prompts the user to enter a single search word.
3. Finds the first occurrence of the search word inside the text using the `.find()` method.
4. If found, prints its 0-based index: `Index: <index>`.
5. If not found, prints: `Word not found`.

### Example 1
```text
Enter text: Hello world, welcome to C++ programming.
Enter word: welcome
Index: 13
```

### Example 2
```text
Enter text: Hello world
Enter word: java
Word not found
```

---

## How to Test
To test your program manually, compile it using:
```bash
make word-search
./word-search
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/6/word-search
```

## Submit Your Code
Make sure you are in the `word-search` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/6/word-search
```
