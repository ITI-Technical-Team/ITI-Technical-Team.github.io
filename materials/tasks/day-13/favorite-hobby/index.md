---
title: Favorite Hobby Webpage
---

# Favorite Hobby Webpage

## Objective
Create a simple webpage about your favorite hobby using HTML and Internal CSS.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir favorite-hobby` to create a folder called `favorite-hobby`
- write `cd favorite-hobby` to go to the `favorite-hobby` folder
- write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

### 1. HTML Elements
Your webpage should contain:
- A `<div>` with the class `container`.
- A main heading (`<h1>`).
- At least two paragraphs (`<p>`).
- An image (`<img>`) with a valid `src`.
- An unordered list (`<ul>`) containing at least 4 hobbies or activities.
- A hyperlink (`<a>`) that opens in a new tab (`target="_blank"`).

### 2. Internal CSS
Add a `<style>` block in the `<head>` of your document. Apply the following styles:
- **General (body):**
  - Set a page background color.
  - Change the text color.
  - Set a suitable font size and line height.
  - Use a Web Safe Font (e.g. Arial, sans-serif).
- **Heading (h1):**
  - Change the heading color.
  - Make it bold using `font-weight: bold`.
  - Center the heading using `text-align: center`.
- **Paragraphs (p):**
  - Change the font style to italic (`font-style: italic`).
  - Add letter spacing.
  - Align the text.
- **Container (.container):**
  - Style the `.container` class with a `width`, `max-width`, `margin`, `padding`, `background-color`, and `border`.
- **Links & Hover:**
  - Style the links (`a`).
  - When the mouse is over the link (`a:hover`), change the text color and add an underline (`text-decoration: underline`).

---

## How to Test
To test your page manually, open `index.html` in your browser.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/13/favorite-hobby
```

## Submit Your Code
Make sure you are in the `favorite-hobby` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/13/favorite-hobby
```
