---
title: "B. Egyptian Food"
---

# B. Egyptian Food

## Background

HTML tables are perfect for laying out content in a grid. You can use them to place text and images side-by-side — like a newspaper or magazine layout.

### Table Anatomy

```html
<table>
  <tr>
    <td>Text column</td>
    <td><img src="..." alt="..."></td>
  </tr>
</table>
```

Key tags for this task:

| Tag | Role |
|-----|------|
| `<table>` | wraps the whole grid |
| `<tr>` | one row in the table |
| `<td>` | one cell in a row (data cell) |
| `<img>` | displays an image |
| `<header>` | semantic page header |
| `<p>` | text paragraph inside a cell |

### Adding an Image

```html
<img src="kushari.jpg" alt="Kushari dish" width="200">
```

> **💡 Tip:**
> You can use free food images from [Unsplash](https://unsplash.com) or [Pexels](https://pexels.com), or search Google Images and download them.

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir table-schedule
  cd table-schedule
  code food.html
  ```

## Problem

Create an **Egyptian Food** showcase page in `food.html` — a visually rich page that looks like a magazine spread, using an HTML table to place text and food images side by side.

### Requirements

1. A proper HTML5 document structure with `<head>` and `<body>`.
2. A `<title>` that reads `Egyptian Food`.
3. A **`<header>`** element at the top of the page containing:
   - An `<h1>` (or similar heading) with `Egyptian Food`
   - A `<p>` subtitle such as `These are the most famous Egyptian food dishes`
4. A **`<table>`** with:
   - At least **3 rows** (`<tr>`), each row containing:
     - A `<td>` with a **text paragraph** (`<p>`) describing a dish
     - A `<td>` with an **`<img>`** of that dish
   - The layout should alternate: `[text | image]` in one row, `[image | text]` in the next (or any consistent pattern)
5. Each row must have **2 cells** (`<td>`): one for text, one for the image.
6. All images must have an `alt` attribute describing the food.
7. There should be at least **3 different food images** in the table.

### Example Row Structure

```html
<tr>
  <td>
    <p>Kushari is Egypt's national dish, a hearty mix of rice, lentils,
    macaroni, and topped with spiced tomato sauce and crispy onions.</p>
  </td>
  <td>
    <img src="kushari.jpg" alt="Kushari dish">
  </td>
</tr>
```

### Expected Page Layout

```
┌─────────────────────────────────────┐
│   <header>                          │
│   EGYPTIAN FOOD                     │
│   These are the most famous...      │
├──────────────────────┬──────────────┤
│  Lorem ipsum text... │  [food img]  │
├──────────────────────┼──────────────┤
│  Lorem ipsum text... │  [food img]  │
├──────────────────────┼──────────────┤
│  Lorem ipsum text... │  [food img]  │
└──────────────────────┴──────────────┘
```

> **📝 Note:**
> The text content (dish descriptions) can be placeholder text like lorem ipsum — the grader checks **structure**, not the exact wording.

## Test Your Code

Make sure you are in the `table-schedule` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/12/table-schedule
```

## Submit Your Code

Make sure you are in the `table-schedule` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/12/table-schedule
```
