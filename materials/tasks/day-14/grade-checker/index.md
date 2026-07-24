---
title: Grade Checker
---

# Grade Checker

## Objective
Write a JavaScript program that checks a student's grade and displays a message based on the score.

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir grade-checker` to create a folder called `grade-checker`
- Write `cd grade-checker` to go to the `grade-checker` folder
- Write `code grade-checker.js` to create a file called `grade-checker.js` and open it in the editor

## Requirements

Write a JavaScript program in `grade-checker.js` that:
1. Declares a variable named `grade` and assigns it a numeric score (e.g. `let grade = 85;`).
2. Uses conditional statements (`if`, `else if`, and `else`) to evaluate the score:
   - If the grade is **90 or above**, display: **"Excellent"**
   - If the grade is **between 75 and 89** (inclusive), display: **"Good"**
   - If the grade is **between 50 and 74** (inclusive), display: **"Pass"**
   - If the grade is **below 50**, display: **"Fail"**
3. Displays the output to the console using `console.log()`.

### Example
If `grade = 85;`, running the script should output:
```text
Good
```

---

## How to Test

To test your program manually, run the script using Node.js in your terminal:
```bash
node grade-checker.js
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/14/grade-checker
```

## Submit Your Code
Make sure you are in the `grade-checker` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/14/grade-checker
```
