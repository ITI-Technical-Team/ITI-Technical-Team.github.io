---
title: "A. Quote of the Day"
---

# A. Quote of the Day

## Background

Creating a random generator is a great way to practice mathematical operators like `Math.random()` and `Math.floor()`. In this task, you will store quotes inside an object and pick one randomly when a user clicks a button.

### Random Numbers

`Math.random()` returns a decimal number between `0` (inclusive) and `1` (exclusive). To get a random integer from `0` to `9` (inclusive), multiply it by `10` and round down using `Math.floor()`:

```javascript
let randomNumber = Math.floor(Math.random() * 10);
```

### Storing Data in an Object

You can use an object to store key-value pairs where the keys are indices (numbers as strings):

```javascript
let quotes = {
    0: { author: "--Oscar Wilde", quote: "Be yourself; everyone else is already taken." },
    1: { author: "--Marilyn Monroe", quote: "I'm selfish, impatient and a little insecure..." }
};
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir color-changer
  cd color-changer
  code index.html
  ```

## Problem

Create a **Quote of the Day** app in `index.html`.

### Requirements

**HTML Structure**

1. A page title of `Quote of the Day`.
2. A heading `<h1>Quote of the Day</h1>`.
3. A button labeled `New Quote`.
4. Two separate areas (e.g. `<p id="quote">` and `<p id="author">`) to display:
   - The quote text
   - The author's name
5. A `<script>` tag containing your JavaScript.

**JavaScript Logic**

1. Store 10 different quotes in an object named `quotes`, where each entry has `quote` and `author`. Use the following quotes:
   - **0**: Oscar Wilde - "Be yourself; everyone else is already taken."
   - **1**: Marilyn Monroe - "I'm selfish, impatient and a little insecure..."
   - **2**: Frank Zappa - "So many books, so little time."
   - **3**: Albert Einstein - "Two things are infinite: the universe and human stupidity; and I'm not sure about the universe."
   - **4**: Marcus Tullius Cicero - "A room without books is like a body without a soul."
   - **5**: Bernard M. Baruch - "Be who you are and say what you feel, because those who mind don't matter, and those who matter don't mind."
   - **6**: Dr. Seuss - "You know you're in love when you can't fall asleep because reality is finally better than your dreams."
   - **7**: Mae West - "You only live once, but if you do it right, once is enough."
   - **8**: Mark Twain - "If you tell the truth, you don't have to remember anything."
   - **9**: Elbert Hubbard - "A friend is someone who knows all about you and still loves you."
2. Write a function `RandomQuotes()` (or triggerable click handler) that runs when the button is clicked:
   - Pick a random number between 0 and 9 using `Math.random()` and `Math.floor()`.
   - Update the HTML text content of `#quote` and `#author` with the randomly selected quote and its author.
3. Wire the button to run the function using `onclick="..."` or `addEventListener()`.

**CSS Styling**

Style the page using a `<style>` block in `<head>` to look centered and visually appealing (e.g. margin, container background, custom fonts).

## Test Your Code

Make sure you are in the `color-changer` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/16/color-changer
```

## Submit Your Code

Make sure you are in the `color-changer` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/16/color-changer
```
