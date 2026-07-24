---
title: Personal Information
---

# Personal Information

## Objective
Create a simple webpage that displays personal information using JavaScript.

## Problem Setup
- Open [CS50 IDE](https://cs50.dev)
- Write `cd` in the *terminal* to go to the home directory
- Write `mkdir personal-info` to create a folder called `personal-info`
- Write `cd personal-info` to go to the `personal-info` folder
- Write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

Create a webpage in `index.html` that contains:
1. **HTML Elements:**
   - A heading (e.g. `<h1>Personal Profile</h1>`).
   - A paragraph (e.g. `<p id="info"></p>`).
   - A button (e.g. `<button id="welcome-btn">Change Message</button>`).
2. **JavaScript:**
   - Use Internal JavaScript (inside a `<script>` tag).
   - Declare variables for:
     - `name` (a string containing your name).
     - `age` (a number containing your age).
     - `favoriteColor` (a string containing your favorite color).
   - Display these values inside the paragraph when the page loads (e.g., "My name is Alice, I am 20 years old, and my favorite color is Blue.").
   - Add a click event handler (using `onclick` or `addEventListener`) to the button. When clicked, change the paragraph text to: **"Welcome to JavaScript!"**.

---

## How to Test

To test your program manually, open the page in your browser and click the button to verify the message changes to "Welcome to JavaScript!".

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/14/personal-info
```

## Submit Your Code
Make sure you are in the `personal-info` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/14/personal-info
```
