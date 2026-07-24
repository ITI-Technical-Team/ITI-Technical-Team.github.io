---
title: Event Practice
---

# Event Practice

## Objective
Practice listening to user events in JavaScript using both **Inline Events** (attributes in HTML) and standard dynamic event listeners (`addEventListener`).

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir event-practice` to create a folder called `event-practice`
- Write `cd event-practice` to go to the `event-practice` folder
- Write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

Write a webpage in `index.html` that contains:
1. **HTML Structure:**
   - A `<button>` element.
   - A text input element (`<input type="text">`).
   - A `<script>` tag.
2. **JavaScript & Events Logic:**
   - **Inline Event Listener:** Add an inline event listener attribute (such as `onclick="..."` or `onmouseover="..."`) directly to the `<button>` element in your HTML. Bind it to a function defined in your script.
   - **addEventListener:** Select the text input element and attach an event listener to it in JavaScript using `addEventListener` (listening to common input events like `keyup`, `change`, `input`, `focus`, or `blur`).
   - Implement custom behavior (like updating the page content, displaying an alert, or logging to the console) for both events to confirm they trigger successfully.

---

## How to Test

To test your webpage manually:
- Open `index.html` in your browser.
- Interact with the button and type inside the text input to check that your event handlers execute correctly.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/16/event-practice
```

## Submit Your Code
Make sure you are in the `event-practice` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/16/event-practice
```
