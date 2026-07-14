---
title: "C. DOM Paragraph Editor"
---

# C. DOM Paragraph Editor

## Background

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content.

### Selecting Multiple Elements

You can select all elements matching a class name using `document.querySelectorAll()`:

```javascript
let paragraphs = document.querySelectorAll(".info");
// querySelectorAll returns a NodeList which you can iterate over
```

### Iterating and Modifying HTML

You can use `.forEach()` to loop through the matching elements, read their text content, modify it, and write it back:

```javascript
paragraphs.forEach((para) => {
    let original = para.textContent;
    let updated = original.toUpperCase().replace("PARAGRAPH", "SENTENCE");
    para.innerHTML = `<span class="edited">${updated}</span>`;
});
```

### Appending Text

You can append text to an element's existing content using the `+=` operator on `innerHTML` or `innerText`:

```javascript
let title = document.querySelector("#title");
title.innerHTML += " - Edited";
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir paragraph-editor
  cd paragraph-editor
  code index.html
  ```

## Problem

Create a **Dynamic Paragraph Editor** in `index.html`.

### Requirements

**HTML Structure**

1. A page title of `DOM Paragraph Editor`.
2. A heading with `id="title"` containing `Welcome to JavaScript!`.
3. Exactly **three** paragraphs with `class="info"`, containing the text:
   - `This is the first paragraph.`
   - `This is the second paragraph.`
   - `This is the third paragraph.`
4. A button labeled `Edit Paragraphs` that calls a function `editParagraphs()` when clicked.
5. A `<script>` tag containing your JavaScript.

**JavaScript Logic**

Define the function `editParagraphs()` to run when the button is clicked:
1. Select all elements with class `info` using `querySelectorAll()`.
2. Loop through each paragraph using `forEach()`.
3. For each paragraph:
   - Read its text content.
   - Convert its text to uppercase using `.toUpperCase()`.
   - Replace the word `"PARAGRAPH"` with `"SENTENCE"` using `.replace()`.
   - Update the paragraph content using `innerHTML` to wrap the new text in a `<span class="edited">` tag (e.g. `<span class="edited">THIS IS THE FIRST SENTENCE.</span>`).
4. Select the heading `#title` and append `" - Edited"` to its text content using `innerHTML` or `innerText` (e.g., it becomes `Welcome to JavaScript! - Edited`).

**CSS Styling**

1. Style your page using basic CSS inside `<style>` tags to center the content.
2. Style the `.edited` class with a green color and bold font so that updated paragraph text turns green and bold when edited.

## Test Your Code

Make sure you are in the `paragraph-editor` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/15/dom-builder
```

## Submit Your Code

Make sure you are in the `paragraph-editor` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/15/dom-builder
```
