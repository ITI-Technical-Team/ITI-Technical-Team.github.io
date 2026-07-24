---
title: Substring Extractor
---

# Substring Extractor

## Objective
Write a C++ program that reads a string, a starting index, and a length, and prints the substring extracted from it.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir substring-extractor` to create a folder called `substring-extractor`
- write `cd substring-extractor` to go to the `substring-extractor` folder
- write `code substring-extractor.cpp` to create a file called `substring-extractor.cpp` and open it in the editor

## Requirements

Write a C++ program in `substring-extractor.cpp` that:
1. Prompts the user to enter a line of text using `getline`.
2. Prompts the user to enter a starting index (integer) and a length (integer).
3. Prints the original string's length using the `.length()` or `.size()` method.
4. Validates that the starting index is within the string bounds (i.e., not negative and less than the string's length).
   - If the index is out of bounds, print `Invalid index`.
   - Otherwise, extract and print the substring of the specified length starting at the index using `.substr()`.

### Example 1
```text
Enter text: Programming
Enter start index: 3
Enter length: 5
Original length: 11
Substring: gramm
```

### Example 2
```text
Enter text: Programming
Enter start index: 15
Enter length: 2
Original length: 11
Invalid index
```

---

## How to Test
To test your program manually, compile it using:
```bash
make substring-extractor
./substring-extractor
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/06/substring-extractor
```

## Submit Your Code
Make sure you are in the `substring-extractor` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/06/substring-extractor
```
