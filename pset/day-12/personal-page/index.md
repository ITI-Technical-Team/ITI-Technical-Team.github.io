---
title: "A. My Web Dev Portfolio"
---

# A. My Web Dev Portfolio

## Background

HTML is the skeleton of every webpage. A well-structured HTML5 document uses **semantic elements** — tags that carry meaning about their content:

| Tag | Meaning |
|-----|---------|
| `<header>` | introductory section at the top of a page |
| `<footer>` | closing section (copyright, contact links) |
| `<figure>` | self-contained media (image + caption) |
| `<figcaption>` | caption that belongs to a `<figure>` |
| `<strong>` | text of **strong importance** (bold) |
| `<em>` | **emphasized** text (italic) |

### Lists

```html
<!-- Unordered list (bullet points) -->
<ul>
  <li>MDN Web Docs</li>
  <li>W3Schools</li>
  <li>CSS-Tricks</li>
</ul>

<!-- Ordered list (numbered) -->
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
```

### Figures with Captions

```html
<figure>
  <img src="project.jpg" alt="My project screenshot">
  <figcaption>
    My first web project —
    <a href="https://www.google.com">search on Google</a>
  </figcaption>
</figure>
```

### Multi-page Navigation

```html
<!-- On index.html: link to contact page -->
<a href="contact.html">Contact Me</a>

<!-- On contact.html: link back to index -->
<a href="index.html">Back to Home</a>
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir personal-page
  cd personal-page
  code index.html
  ```

## Problem

Create an HTML webpage to **showcase your web development skills and knowledge**. The page should be clean, well-structured, and user-friendly.

### Required Tags

> `<head>`, `<body>`, `<header>`, `<footer>`, `<p>`, `<ul>`, `<ol>`, `<a>`, `<img>`, `<figure>`

### Requirements — `index.html`

1. Use the `<head>` tag and include a `<title>` tag.
2. Use the `<body>` tag, and within it:
   - A **`<header>`** welcoming the visitor (e.g. `Welcome`).
   - A brief introductory **paragraph** about yourself using `<p>`.
3. Add an **unordered list** (`<ul>`) that displays your top **3 favourite websites** for learning web development.
4. Add an **ordered list** (`<ol>`) to showcase **at least 3 of your web development skills**.
5. Add an **image** of something you like inside a **`<figure>`** element with a **`<figcaption>`** caption beneath it. (Maximum of 3 images.)
6. Add a **hyperlink** (`<a href="https://www.google.com">`) to Google — place it inside one of your paragraphs or inside the `<figcaption>`.
7. Add a **link to your contact page** (e.g. `<a href="contact.html">Contact Me</a>`).
8. Make **one paragraph `<strong>`** (bold/important) and **another paragraph `<em>`** (italic/emphasized).
9. Include a **`<footer>`** with a copyright notice (e.g. `&copy; 2025 Your Name`).

### Requirements — `contact.html`

Create a second file `contact.html` in the **same folder** with:

1. Your **phone number** and **email address** displayed on the page.
2. An **anchor link back to the index** page: `<a href="index.html">Back to Home</a>`.

### Expected Structure (Outline)

```
index.html
├── <head> → <title>
└── <body>
    ├── <header>Welcome</header>
    ├── <p><strong>About me...</strong></p>
    ├── <p><em>My first HTML project</em></p>
    ├── <ul> → 3 fav websites
    ├── <ol> → web dev skills
    ├── <figure>
    │   ├── <img src="..." alt="...">
    │   └── <figcaption>... <a href="https://www.google.com">Google</a></figcaption>
    ├── <a href="contact.html">Contact Me</a>
    └── <footer>&copy; 2025 Your Name</footer>

contact.html
├── phone number & email
└── <a href="index.html">Back to Home</a>
```

> **❗ Important:**
> You must submit **both** `index.html` and `contact.html`. The grader checks for both files.

## Test Your Code

Make sure you are in the `personal-page` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/12/personal-page
```

## Submit Your Code

Make sure you are in the `personal-page` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/12/personal-page
```
