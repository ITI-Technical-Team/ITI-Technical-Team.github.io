---
title: Online Course Registration
---

# Online Course Registration

## Objective
Create a simple webpage for an online course registration.

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir course-registration` to create a folder called `course-registration`
- write `cd course-registration` to go to the `course-registration` folder
- write `code index.html` to create a file called `index.html` and open it in the editor

## Requirements

### 1. Header
Create a `<header>` that displays the academy name.

### 2. Navigation
Create a `<nav>` with the following links:
- Home
- Courses
- Register

### 3. Available Courses Section
Create a `<section>` that contains a table listing the following course information:

| Course | Duration |
| :--- | :--- |
| HTML | 2 Weeks |
| CSS | 3 Weeks |
| JavaScript | 5 Weeks |

The table must include:
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `<tr>`
- `<th>`
- `<td>`

The table footer (`<tfoot>`) should display: `Total Courses: 3`

### 4. Registration Form
Create a `<form>` that contains the following fields:
- Name input
- Email input
- Password input
- Feedback or Goals (`<textarea>`)
- Department dropdown (`<select>`) with the following options:
  - Frontend
  - Backend
  - Full Stack
- Submit button

Each input must have a corresponding `<label>`.

### 5. Footer
Create a `<footer>` with a copyright message.

---

## How to Test
To test your page manually, open `index.html` in your browser.

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/12/course-registration
```

## Submit Your Code
Make sure you are in the `course-registration` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/12/course-registration
```
