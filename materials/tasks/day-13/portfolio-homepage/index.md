---
title: Personal Portfolio Homepage
---

# Personal Portfolio Homepage

## Objective
Create a simple personal portfolio homepage styled using External CSS.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir portfolio-homepage` to create a folder called `portfolio-homepage`
- write `cd portfolio-homepage` to go to the `portfolio-homepage` folder
- write `code index.html` to create a file called `index.html` and open it in the editor
- write `code style.css` to create a stylesheet file called `style.css` and open it in the editor

## Requirements

### 1. HTML Elements
Create an `index.html` page that includes:
- A link to your external stylesheet: `<link rel="stylesheet" href="style.css">`.
- A `<div>` with the class `container`.
- A `<header>` containing your name and a short introduction.
- A Skills section containing an unordered list (`<ul>`) with at least 5 skills.
- A Projects section containing a paragraph (`<p>`) describing your projects.
- A Contact Me hyperlink (`<a>`).

### 2. External CSS (style.css)
In `style.css`, apply the following style rules using a combination of **Element Selectors**, **one Class Selector** (for `.container`), and **one ID Selector** (for your contact link):
- **Colors:** Use color names, Hexadecimal, or RGB values for background and text colors.
- **Typography:** Set `font-family`, `font-size`, `font-weight`, `font-style`, `line-height`, `letter-spacing`, and `text-align`.
- **Container styling (.container):**
  - Style the `.container` class with `width`, `max-width`, `margin`, `padding`, `background-color`, and `border`.
- **Links & Hover:**
  - Style the Contact Me link.
  - When the mouse is over the Contact Me link (`a:hover` or `#id:hover`), change the text color and add/remove the underline using `text-decoration`.

---

## How to Test
To test your page manually, open `index.html` in your browser.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/13/portfolio-homepage
```

## Submit Your Code
Make sure you are in the `portfolio-homepage` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/13/portfolio-homepage
```
