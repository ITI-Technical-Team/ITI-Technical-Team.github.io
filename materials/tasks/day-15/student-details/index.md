---
title: Student Details
---

# Student Details

## Objective
Create a JavaScript object representing a student, print its details, update one of its properties, and print the updated object.

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir student-details` to create a folder called `student-details`
- Write `cd student-details` to go to the `student-details` folder
- Write `code student-details.js` to create a file called `student-details.js` and open it in the editor

## Requirements

Write a JavaScript program in `student-details.js` that:
1. Declares an object named `student` with the following properties:
   - `name` (string)
   - `age` (number)
   - `department` (string)
2. Displays the student object's information to the console using `console.log()`.
3. Modifies the student's `age` property to a different value.
4. Displays the updated student object to the console.

### Example Output
```text
Original Student Object:
{ name: 'John Doe', age: 20, department: 'Computer Science' }

Updated Student Object:
{ name: 'John Doe', age: 21, department: 'Computer Science' }
```

---

## How to Test

To test your program manually, run the script using Node.js in your terminal:
```bash
node student-details.js
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/15/student-details
```

## Submit Your Code
Make sure you are in the `student-details` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/15/student-details
```
