---
title: "B. Navigation Bar"
---

# B. Navigation Bar

## Background

A navigation bar is one of the most common components on any website. Creating one involves styling anchor (`<a>`) tags inside a `<nav>` container.

### Flexbox and Text Alignment

To align links horizontally, we can use `text-align: center` on the container or lay them out using Flexbox. For this simple task, centering text inside the container is sufficient:

```css
.navbar {
    background-color: #222;
    padding: 15px;
    text-align: center;
}
```

### Styling Anchor Links

By default, browsers style links with a blue color and an underline. We can override this using CSS:

```css
.navbar a {
    color: white;                  /* white text */
    text-decoration: none;         /* remove default underline */
    margin-right: 20px;            /* add space between links */
    font-size: 20px;
}
```

### Hover Effects

The `:hover` pseudo-class allows you to change the style of an element when a user hovers their mouse over it:

```css
.navbar a:hover {
    text-decoration: underline;    /* add underline on hover */
    color: yellow;                 /* change color to yellow */
}
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir navbar-example
  cd navbar-example
  code index.html
  ```

## Problem

Create a styled navigation bar in `index.html`.

### Requirements

**HTML** — `index.html` must contain:

1. A `<nav>` element with a class name of `navbar`.
2. At least **3 anchor links** (`<a>`) inside the `<nav>` with the texts: `Home`, `About`, and `Contact`.

**CSS** — applied via a `<style>` block in `<head>` (or an external CSS file) — must set:

1. A **dark background color** for the `.navbar` container (e.g. `#222`).
2. Links (`.navbar a`) with **white text**.
3. **No underline** by default (`text-decoration: none`).
4. **Space between links** (using `margin-right` or padding).
5. A **hover effect** (`.navbar a:hover`) that underlines the link when the mouse is over it.

### Expected Result

```
┌────────────────────────────────────────────────────────┐
│             Home      About      Contact               │ (Dark Background)
└────────────────────────────────────────────────────────┘
```

> **📝 Note:**
> You can place all of your HTML and CSS inside `index.html` using a `<style>` tag, or separate them into `index.html` and a `.css` file. The grader accepts both.

## Test Your Code

Make sure you are in the `navbar-example` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/13/box-model-card
```

## Submit Your Code

Make sure you are in the `navbar-example` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/13/box-model-card
```
