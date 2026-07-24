---
title: Change Multiple Paragraphs
---

# Change Multiple Paragraphs

## Objective
Create a webpage containing three paragraphs and a button, and use JavaScript (`querySelectorAll`) to update the text content of all paragraphs when the button is clicked.

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir change-paragraphs` to create a folder called `change-paragraphs`
- Write `cd change-paragraphs` to go to the `change-paragraphs` folder
- Write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

Write a webpage in `index.html` that contains:
1. **HTML Structure:**
   - Three separate paragraph elements (`<p>`).
   - One button.
   - A `<script>` tag for your JavaScript code.
2. **JavaScript Logic:**
   - Selects all paragraph elements using `document.querySelectorAll()`.
   - Attaches a click event handler to the button.
   - When the button is clicked, loops through the selected paragraphs (e.g. using `.forEach()`) and updates the text content of every paragraph.

---

## How to Test

To test your webpage manually:
- Open `index.html` in your browser.
- Click the button and check that the text of all three paragraphs changes immediately.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/16/change-paragraphs
```

## Submit Your Code
Make sure you are in the `change-paragraphs` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/16/change-paragraphs
```
