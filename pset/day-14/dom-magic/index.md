---
title: "C. Student Grade Calculator"
---

# C. Student Grade Calculator

## Background

Performing mathematical operations and conditional checks is a common task in programming. In this exercise, you will prompt the user for student grades, calculate their average, and determine whether they passed or failed.

### Converting Prompt Inputs

Since `prompt()` returns string values, you must convert them to numbers before adding them together:

```javascript
let grade1 = Number(prompt("Enter grade for Subject 1:"));
```

### Ternary Operator / Conditional Check

You can use an `if-else` statement or a ternary operator to decide the final result:

```javascript
let result = average >= 50 ? "Pass" : "Fail";
```

### Formatting Decimals

To restrict a decimal number to two decimal places, use `.toFixed(2)`:

```javascript
let averageString = average.toFixed(2);
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir grade-calculator
  cd grade-calculator
  code index.html
  ```

## Problem

Create a **Student Grade Calculator** page in `index.html`.

### Requirements

**HTML Structure**

1. A page title of `Student Grade Calculator`.
2. A heading `<h1>Student Grade Calculator</h1>`.
3. A `<script>` tag containing your JavaScript logic.

**JavaScript Logic**

When the page loads, your script must:
1. Ask the user for the student's name: `Enter student name:`.
2. Ask the user for **3 subject grades** using three separate prompts (each converted to a number).
3. Calculate the **total score** (the sum of all three grades).
4. Calculate the **average score** (total divided by 3).
5. Decide if the student passed or failed:
   - If the average score is **50 or more**, the result is `"Pass"`.
   - If the average score is **less than 50**, the result is `"Fail"`.
6. Show all calculated details inside a single popup `alert()` (or using `console.log()`):
   - Student's Name
   - The 3 grades
   - Total score
   - Average score (formatted with 2 decimal places)
   - Final result (Pass or Fail)

**CSS Styling**

1. Center the heading.
2. Style the heading (`<h1>`) with a custom color (e.g. `darkred`).
3. Set a custom font family (e.g. `Arial`) and background color on the body.

## Test Your Code

Make sure you are in the `grade-calculator` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/14/dom-magic
```

## Submit Your Code

Make sure you are in the `grade-calculator` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/14/dom-magic
```
