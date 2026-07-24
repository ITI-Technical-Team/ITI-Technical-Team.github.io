---
title: Change Heading Text
---

# Change Heading Text

## Objective
Create a simple webpage with a heading and a button, and use JavaScript (`querySelector`) to change the heading text when the button is clicked.

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir change-heading` to create a folder called `change-heading`
- Write `cd change-heading` to go to the `change-heading` folder
- Write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

Write a webpage in `index.html` that contains:
1. **HTML Structure:**
   - One heading element (e.g. `<h1>Original Heading Text</h1>`).
   - One button (e.g. `<button>Change Heading</button>`).
   - A `<script>` tag for your JavaScript code.
2. **JavaScript Logic:**
   - Selects the heading element using `document.querySelector()`.
   - Attaches a click event handler to the button (either using inline event attribute or `addEventListener`).
   - When the button is clicked, changes the text content of the heading to a new text of your choice.

---

## How to Test

To test your webpage manually:
- Open `index.html` in your browser.
- Click the button and check that the heading text changes immediately.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/16/change-heading
```

## Submit Your Code
Make sure you are in the `change-heading` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/16/change-heading
```
