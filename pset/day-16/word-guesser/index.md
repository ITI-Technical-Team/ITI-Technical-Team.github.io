---
title: "B. Mood-Based Greeting App"
---

# B. Mood-Based Greeting App

## Background

Combining form inputs, dropdown lists, user objects, dynamic styling, and events is a great way to tie everything you have learned in JavaScript together.

### Live Input Preview

You can listen for the `keyup` event on a text input to create a live preview as the user types:

```javascript
nameInput.addEventListener("keyup", function() {
    preview.textContent = "Typing: " + nameInput.value;
});
```

### Changing CSS Styles in JS

You can modify an element's background and text colors directly using the `style` property:

```javascript
document.body.style.backgroundColor = "#d4edda";
message.style.color = "#155724";
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir word-guesser
  cd word-guesser
  code index.html
  ```

## Problem

Create a **Mood-Based Greeting App** in `index.html` that updates the greeting message, picks a random word-guesserropriate quote, and dynamically colors the page background based on the selected mood.

### Requirements

**HTML Structure**

1. A page title of `User Dashboard`.
2. A heading `<h1>User Mood Dashboard</h1>`.
3. An input field `<input type="text" id="nameInput" placeholder="Enter your name">` for entering a name.
4. An element `<p id="preview"></p>` to display live name preview.
5. A `<select id="moodSelect">` dropdown list containing three options: `Happy`, `Sad`, and `Excited`.
6. A button labeled `Show Message` with `id="showBtn"`.
7. Two elements (e.g. `<p id="message"></p>` and `<p id="quote"></p>`) to show the output greeting and quote.
8. A `<script>` tag containing your JavaScript.

**JavaScript Logic**

1. Use `querySelector` to select all necessary DOM elements.
2. Add a `keyup` event listener on `nameInput`:
   - If the input is not empty, set the preview text content to: `Typing: [value]`.
   - If the input is empty, clear the preview text.
3. Add a `click` event listener on the `showBtn`:
   - Validate the input name: check if its trimmed length is **less than 3 characters**.
     - If invalid, show an alert: `Please enter a valid name with at least 3 letters.` and do not execute anything else.
   - If valid, create a user object with `name` and `mood` properties.
   - Select a random quote from a mood category:
     - **Happy** quotes:
       - "Keep smiling, it makes people wonder what you're up to!"
       - "Happiness is a choice, not a result."
     - **Sad** quotes:
       - "Tough times don't last, but tough people do."
       - "It's okay to not be okay."
     - **Excited** quotes:
       - "Dream big and dare to fail!"
       - "Do something today that your future self will thank you for."
   - Display the greeting: `Hello [name]! You seem [mood] today` (with bold formatting).
   - Display the random quote inside quotes: `"[selectedQuote]"`.
   - Dynamic Styling: Change body background and text color based on mood:
     - **Happy**: body background = `#d4edda`, message color = `#155724`
     - **Sad**: body background = `#f8d7da`, message color = `#721c24`
     - **Excited**: body background = `#fff3cd`, message color = `#856404`

## Test Your Code

Make sure you are in the `word-guesser` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/16/word-guesser
```

## Submit Your Code

Make sure you are in the `word-guesser` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/16/word-guesser
```
