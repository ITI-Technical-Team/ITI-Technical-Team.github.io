---
title: "A. Card Layout"
---

# A. Card Layout

## Background

CSS gives you control over how HTML elements look. Three of the most important properties for building a **card** component are:

```css
.card {
    border: 1px solid lightgray;     /* draw a border around the element */
    border-radius: 10px;             /* round the corners */
    padding: 20px;                   /* space between content and the border */
    max-width: 400px;                /* don't grow wider than 400 px */
    margin: 50px auto;               /* centre the card horizontally */
}
```

### Internal vs External CSS

CSS can be written **inside the same HTML file** using a `<style>` tag:

```html
<head>
    <style>
        .card {
            border: 1px solid lightgray;
        }
    </style>
</head>
```

Or in a **separate `.css` file** linked with `<link>`. For this task either approach is accepted.

### Applying a class

```html
<div class="card">
    <h2>Card Title</h2>
    <p>Text inside the card.</p>
</div>
```

The class name `card` in CSS (`selector = .card`) matches `class="card"` in HTML.

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir card-layout
  cd card-layout
  code index.html
  ```

## Problem

Create a **card** layout in `index.html` that looks clean and centred on the page.

### Requirements

**HTML** — `index.html` must contain:

1. A `<div>` with a `class` attribute (e.g. `class="card"`).
2. An `<h2>` inside the div for the card title.
3. A `<p>` inside the div for the card text.

**CSS** — applied via `<style>` in the `<head>` (or an external `.css` file) — must set:

1. A **border** with a light gray colour (`lightgray` or any grey value).
2. Rounded corners using **`border-radius`**.
3. **`padding`** inside the card.
4. A **`max-width`** to limit the card width.

### Expected Result

```
        ┌──────────────────────────────┐
        │  Card Title                  │
        │                              │
        │  This is some text inside    │
        │  the card. The card has a    │
        │  border, rounded corners,    │
        │  and padding.                │
        └──────────────────────────────┘
```

The card should be **centred on the page** and have visible rounded corners.

## Test Your Code

Make sure you are in the `card-layout` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/13/style-me
```

## Submit Your Code

Make sure you are in the `card-layout` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/13/style-me
```
