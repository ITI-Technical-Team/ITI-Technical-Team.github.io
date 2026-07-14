---
title: "C. Registration Form"
---

# C. Registration Form

## Background

HTML forms allow users to enter and submit data. Beyond basic inputs, you can group related fields using `<fieldset>` and label the group with `<legend>`:

```html
<form>
  <fieldset>
    <legend>Personal Data</legend>

    <label for="fname">First Name:</label>
    <input type="text" id="fname" name="fname" placeholder="ex: ahmed">

    <label for="lname">Second Name:</label>
    <input type="text" id="lname" name="lname" placeholder="ex: niyad">
  </fieldset>
</form>
```

### All Input Types Used in This Task

| Type | HTML | Purpose |
|------|------|---------|
| `text` | `<input type="text">` | names, phone number |
| `email` | `<input type="email">` | email address |
| `password` | `<input type="password">` | masked input |
| `radio` | `<input type="radio">` | one choice from a group |
| `checkbox` | `<input type="checkbox">` | tick-able option |
| `submit` | `<input type="submit">` | sends the form |
| `reset` | `<input type="reset">` | clears all fields |

### Drop-down with `<select>`

```html
<select name="university">
  <option value="auc">AUC</option>
  <option value="cairo">Cairo University</option>
  <option value="ain">Ain Shams</option>
</select>
```

### Photo / Image Upload

```html
<input type="file" name="photo" accept="image/*">
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir html-form
  cd html-form
  code register.html
  ```

## Problem

Build a **Personal Data registration form** in `register.html` that matches the layout shown below. It should use a `<fieldset>` to group fields, and include all the input types listed.

### Requirements

1. Proper HTML5 document structure with `<title>` = `Course Registration`.
2. A **`<form>`** element.
3. A **`<fieldset>`** with a **`<legend>`** that reads `Personal Data`.
4. Inside the fieldset, a **photo upload** area:
   - A label (`Your Name` or similar) and a file input **or** an image placeholder.
5. **First Name** — `<input type="text">` with `placeholder="ex: ahmed"` and a `<label>`.
6. **Second Name** — `<input type="text">` with `placeholder="ex: niyad"` and a `<label>`.
7. **Phone** — `<input type="text">` with a `<label>` for `Your Phone`.
8. **Email** — `<input type="email">` with a `<label>`.
9. **Password** — `<input type="password">` with a `<label>`.
10. **Repassword** — a second `<input type="password">` with a `<label>` for `Repassword`.
11. **Gender** — **2 radio buttons** (`Male`, `Female`) each with a `<label>`.
12. **Status** — **2 checkboxes** (`Student`, `Graduated`) each with a `<label>`.
13. A **`<select>`** drop-down for university with at least **3 `<option>`** items.
14. A **`<input type="submit">`** button with value `SUBMIT`.
15. A **`<input type="reset">`** button with value `RESET`.

### Visual Reference

```
┌─ Personal Data ──────────────────────────────┐
│  [photo upload area]                          │
│                                               │
│  First Name   : [____________] ex ahmed       │
│  Second Name  : [____________] ex niyad       │
│                                               │
│  Your Phone   : [____________]                │
│  Email        : [____________]                │
│  Password     : [____________]                │
│  Repassword   : [____________]                │
│                                               │
│  ○ Male   ○ Female                           │
│                                               │
│  ☐ Student   ☐ Graduated                    │
│                                               │
│  [AUC ▼]                                     │
│                                               │
│  [SUBMIT]  [RESET]                           │
└───────────────────────────────────────────────┘
```

> **❗ Important:**
> The **`<fieldset>`** tag is required — it is highlighted in the task and will be checked.

> **💡 Tip:**
> Use `name="gender"` on both radio buttons so only one can be selected at a time. Use distinct `name` values for the checkboxes.

## Test Your Code

Make sure you are in the `html-form` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/12/html-form
```

## Submit Your Code

Make sure you are in the `html-form` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/12/html-form
```
