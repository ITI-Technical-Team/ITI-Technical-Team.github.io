---
title: "B. Greet User"
---

# B. Greet User

## Background

Interacting with the Document Object Model (DOM) is a core capability of JavaScript. You can listen to user interactions like button clicks and modify the text content on the page in response.

### Click Events

You can trigger a JavaScript function when a button is clicked by using the `onclick` attribute in HTML:

```html
<button onclick="showInfo()">Click Me</button>
```

### Modifying Element Content

To modify the text of a paragraph or header, first select the element by its `id`, then change its `innerText`:

```javascript
document.getElementById("info").innerText = "Hello, " + name + "!";
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir greet-user
  cd greet-user
  code index.html
  ```

## Problem

Create a simple web page in `index.html` that greets the user when they click a button.

### Requirements

**HTML Structure**

1. A page title of `Greet User`.
2. A paragraph element with `id="info"` displaying a default welcome message (e.g. `Welcome!`).
3. A `<button>` element that runs a function called `showInfo()` when clicked.
4. A `<script>` tag containing your JavaScript code.

**JavaScript Logic**

Create a function named `showInfo()` that:
1. Prompts the user for their name: `What is your name?`.
2. Updates the text inside `#info` to read `Hello, [name]!`.
3. Displays a popup `alert()` confirming the update (e.g. `Greeting updated!`).

**CSS Styling**

Style your page to look clean and neat:
1. Center all text on the page (`text-align: center`).
2. Style the `#info` text with a custom font size and color (e.g., `darkblue`).
3. Style the button with padding, custom background color, a white text color, and a `border-radius` to round the corners.

## Test Your Code

Make sure you are in the `greet-user` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/14/calculator
```

## Submit Your Code

Make sure you are in the `greet-user` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/14/calculator
```
