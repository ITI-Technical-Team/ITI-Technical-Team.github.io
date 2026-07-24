---
title: Favorite Day
---

# Favorite Day

## Objective
Display the name of a day of the week based on an input number using a Switch Statement in JavaScript.

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir favorite-day` to create a folder called `favorite-day`
- Write `cd favorite-day` to go to the `favorite-day` folder
- Write `code favorite-day.js` to create a file called `favorite-day.js` and open it in the editor

## Requirements

Write a JavaScript program in `favorite-day.js` that:
1. Declares a variable named `day` and sets it to a numeric value (e.g. `let day = 1;` where 1 represents Sunday, 2 represents Monday, etc.).
2. Uses a `switch` statement to print the name of the day corresponding to the number:
   - `1` -> **"Sunday"**
   - `2` -> **"Monday"**
   - `3` -> **"Tuesday"**
   - `4` -> **"Wednesday"**
   - `5` -> **"Thursday"**
   - `6` -> **"Friday"**
   - `7` -> **"Saturday"**
3. Adds a `default` case to handle invalid day numbers (any value other than 1 to 7) and display an error message (e.g. **"Invalid day"**).
4. Prints the result to the console using `console.log()`.

### Example
If `day = 1;`, running the script should output:
```text
Sunday
```

---

## How to Test

To test your program manually, run the script using Node.js in your terminal:
```bash
node favorite-day.js
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/14/favorite-day
```

## Submit Your Code
Make sure you are in the `favorite-day` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/14/favorite-day
```
