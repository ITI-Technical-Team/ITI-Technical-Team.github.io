---
title: Personal Profile Webpage
---

# Personal Profile Webpage

## Objective
Create a simple personal profile webpage using HTML elements.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir personal-profile` to create a folder called `personal-profile`
- write `cd personal-profile` to go to the `personal-profile` folder
- write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

### 1. Header
Create a `<header>` that contains:
- A main title using `<h1>`.
- A short welcome paragraph using `<p>`.

### 2. Navigation
Create a `<nav>` with the following links:
- Home
- About
- Contact

### 3. About Me Section
Create a `<section>` that contains:
- Your photo using `<img>` (make sure it specifies a `src` attribute).
- A short paragraph introducing yourself. Inside the paragraph text, use:
  - `<strong>` for one important word.
  - `<em>` for one emphasized word.
  - `<span>` to style/color one word.
  - `<br>` to move to a new line.

### 4. Skills
Create an unordered list (`<ul>`) that contains at least 5 skills as `<li>` items.

### 5. Learning Plan
Create an ordered list (`<ol>`) showing at least 4 steps for learning web development as `<li>` items.

### 6. Footer
Create a `<footer>` that contains a copyright message (e.g., using `&copy;` or `©` symbol, the year, and your name).

---

## How to Test
To test your page manually, open `index.html` in your browser.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/12/personal-profile
```

## Submit Your Code
Make sure you are in the `personal-profile` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/12/personal-profile
```
