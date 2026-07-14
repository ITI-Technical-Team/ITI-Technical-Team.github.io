---
title: "C. Simple Contact Form"
---

# C. Simple Contact Form

## Background

Forms are essential for collecting user input. In this task, we will apply CSS to style a form and its input elements to make it clean and readable.

### Display Properties and Sizing

By default, `<label>`, `<input>`, and `<textarea>` elements are inline or inline-block. To make labels stack above their inputs, we can change their display property:

```css
.contact-form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}
```

To make inputs fill the width of the form container, we set `width: 100%`. We also use `box-sizing: border-box` to ensure padding doesn't make the elements overflow:

```css
.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;       /* includes padding/border in the width */
}
```

### Styling Buttons and Hover Effects

Buttons can be styled with custom background colors, padding, and hover states to feel responsive:

```css
.contact-form button {
    background-color: #0077aa;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact-form button:hover {
    background-color: #01293b;   /* darker background color on hover */
}
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir contact-form
  cd contact-form
  code index.html
  ```

## Problem

Create a styled contact form in `index.html`.

### Requirements

**HTML** — `index.html` must contain:

1. A `<form>` element (e.g. with `class="contact-form"`).
2. Inside the form, you must include:
   - A `<label>` and `<input>` (type `text` or similar) for **Name**.
   - A `<label>` and `<input>` (type `email`) for **Email**.
   - A `<label>` and `<textarea>` for **Message**.
   - A `<button>` with `type="submit"` to send the form.

**CSS** — applied via a `<style>` block in `<head>` (or an external CSS file) — must set:

1. **Width and Padding** for both the `<input>` and `<textarea>` fields.
2. **Margin** on form elements to space them out vertically.
3. A styled submit button containing:
   - A custom **background color**.
   - **White text** color.
   - **Padding** inside the button.
   - A **hover effect** (`button:hover`) that changes the background color.

### Expected Layout

```
    ┌───────────────────────────────────┐
    │ Name                              │
    │ [ Enter your name               ] │
    │                                   │
    │ Email                             │
    │ [ Enter your email              ] │
    │                                   │
    │ Message                           │
    │ [ Write your message here...    ] │
    │ [                               ] │
    │                                   │
    │ [ Send ]                          │
    └───────────────────────────────────┘
```

> **📝 Note:**
> Make sure your HTML inputs match their labels correctly (using `for` and `id` attributes).

## Test Your Code

Make sure you are in the `contact-form` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/13/navbar-style
```

## Submit Your Code

Make sure you are in the `contact-form` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/13/navbar-style
```
