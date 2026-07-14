---
title: "A. Age Category Checker"
---

# A. Age Category Checker

## Background

JavaScript allows us to make web pages interactive by executing code based on user input. In this task, you will write a program that checks a user's age category using an **arrow function** and updates the page styling dynamically.

### Arrow Functions

Arrow functions are a modern way to write functions in JavaScript:

```javascript
const checkAge = (age) => {
    // function body
};
```

### Prompt and Numbers

The `prompt()` function always returns a **string**. If you want to perform numerical comparisons (like `<` or `>=`), you should convert the input to a number first using `Number()`:

```javascript
let userAge = prompt("Enter your age:");
let ageAsNumber = Number(userAge);
```

### Dynamic Styling with Classes

You can change the style of an HTML element by modifying its class name in JavaScript:

```javascript
const resultElement = document.getElementById("result");
resultElement.className = "child"; // applies the .child CSS rule
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir age-checker
  cd age-checker
  code index.html
  ```

## Problem

Create an **Age Category Checker** page in `index.html`.

### Requirements

**HTML Structure**

1. A page title of `Age Category Checker`.
2. A heading `<h1>Check Your Age Category</h1>`.
3. An element (e.g. `<p id="result">`) where the category result text will be displayed.
4. A `<script>` block containing your JavaScript code.

**JavaScript Logic**

1. Ask the user for their age using a `prompt()` when the page loads.
2. Define an **arrow function** named `checkAge` that accepts a numerical age:
   - If the age is **less than 13**, the category is `"Child"`.
   - If the age is **between 13 and 17** (inclusive), the category is `"Teenager"`.
   - If the age is **18 or older**, the category is `"Adult"`.
3. Inside this function:
   - Display the result text to the user using an `alert()`.
   - Update the text content of your result element (e.g. `You are a Child.`, `You are a Teenager.`, or `You are an Adult.`).
   - Add a class name to the result element corresponding to the category (e.g., `child`, `teenager`, or `adult`).
4. Call `checkAge()` passing the converted number from the user's prompt.

**CSS Styling**

1. Give the page a light background color (e.g. `#f0f8ff`).
2. Center all content on the page (`text-align: center`).
3. Create CSS classes to style the result text with different colors depending on the category:
   - `.child` (e.g. blue)
   - `.teenager` (e.g. orange)
   - `.adult` (e.g. green)

## Test Your Code

Make sure you are in the `age-checker` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/14/js-basics
```

## Submit Your Code

Make sure you are in the `age-checker` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/14/js-basics
```
