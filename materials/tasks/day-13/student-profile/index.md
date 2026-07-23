---
title: Student Profile Card
---

# Student Profile Card

## Objective
Create a styled student profile card.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir student-profile` to create a folder called `student-profile`
- write `cd student-profile` to go to the `student-profile` folder
- write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

### 1. HTML Elements
Your webpage should contain:
- A `<div>` with the id `profile`.
- Inside the profile `<div>`, add:
  - A student photo (`<img>`).
  - Student name using `<h1>` with the class `title`.
  - A short description paragraph (`<p>`).
  - An ordered list (`<ol>`) of learning goals.
  - A portfolio link (`<a>`).

### 2. Internal CSS
Add a `<style>` block in the `<head>` of your document. Apply the following styles:
- **ID Selector (#profile):**
  - Style the profile card container using its ID selector (`#profile`). Specify a `width`, `max-width`, `margin`, `padding`, `background-color`, and `border`.
- **Class Selector (.title):**
  - Style the student name heading using its class selector (`.title`).
- **General Styling & Box Model:**
  - Apply background color, text color, font family, font size, font weight, line height, letter spacing, and text alignment.
  - Apply proper borders, padding, and margins for the card.
- **Link & Hover Selector:**
  - Style the portfolio link (`a`).
  - Under `a:hover`, change the link color and add or remove the underline using `text-decoration`.

---

## How to Test
To test your page manually, open `index.html` in your browser.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/13/student-profile
```

## Submit Your Code
Make sure you are in the `student-profile` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/13/student-profile
```
