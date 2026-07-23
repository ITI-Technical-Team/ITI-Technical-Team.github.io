---
title: My Portfolio Website
---

# My Portfolio Website

## Objective
Create a simple personal portfolio webpage using only the HTML elements covered in class.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir portfolio-website` to create a folder called `portfolio-website`
- write `cd portfolio-website` to go to the `portfolio-website` folder
- write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

### 1. Header
Create a `<header>` that contains:
- Your name using `<h1>`.
- Your job title using `<p>`.

### 2. Navigation
Create a `<nav>` with the following links:
- Home
- About
- Skills
- Projects
- Contact

### 3. About Me Section
Create a `<section>` that contains a `<div>` with:
- Your photo using `<img>`.
- Two paragraphs describing yourself. Use the following formatting elements inside the text:
  - `<strong>`
  - `<em>`
  - `<b>`
  - `<i>`
  - `<span>`
  - `<br>`

### 4. Skills Section
Create a `<section>` that contains:
- An unordered list (`<ul>`) containing at least 5 skills.
- An ordered list (`<ol>`) showing the steps to become a web developer.

### 5. Projects Section
Create a `<section>` that contains a table listing the following project information:

| Project | Technology | Status |
| :--- | :--- | :--- |
| Portfolio | HTML | Completed |
| Calculator | HTML | In Progress |
| Registration Form | HTML | Completed |

The table must include:
- `<thead>`
- `<tbody>`
- `<tfoot>`

The table footer (`<tfoot>`) should display: `Total Projects: 3`

### 6. Contact Section
Create a `<section>` containing a `<form>` with the following fields:
- Name input
- Email input
- Password input
- Message (`<textarea>`)
- Department (`<select>`) dropdown with the following options:
  - Frontend
  - Backend
  - Full Stack
- Submit button

Each input must have a corresponding `<label>`.

### 7. Footer
Create a `<footer>` containing a copyright message.

---

## How to Test
To test your page manually, open `index.html` in your browser.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/12/portfolio-website
```

## Submit Your Code
Make sure you are in the `portfolio-website` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/12/portfolio-website
```
