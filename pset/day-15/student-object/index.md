---
title: "A. Company Info Viewer"
---

# A. Company Info Viewer

## Background

JavaScript objects are used to store collections of data. An object is defined with curly braces `{}` and contains comma-separated key-value pairs (properties).

### Objects and Arrays

An object property can hold any data type, including arrays or even other objects:

```javascript
let company = {
    name: "TechCorp",
    employees: [
        { name: "Alice", role: "Developer" },
        { name: "Bob", role: "Designer" }
    ]
};
```

### Accessing Object Properties

Properties can be accessed using dot notation:

```javascript
console.log(company.name);                  // "TechCorp"
console.log(company.employees[0].name);     // "Alice"
```

### Looping Over Arrays of Objects

You can use a `for` loop to iterate through an array stored inside an object:

```javascript
for (let i = 0; i < company.employees.length; i++) {
    console.log("Name: " + company.employees[i].name);
}
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir student-object
  cd student-object
  code index.html
  ```

## Problem

Create a **Company Info Viewer** in `index.html`.

### Requirements

**HTML Structure**

1. A page title of `Company Info - Objects Task`.
2. A heading `<h1>Object Task: Company Info</h1>`.
3. A `<button>` labeled `Show Info` that calls a function named `showInfo()` when clicked.
4. A `<script>` tag containing your JavaScript.

**JavaScript Logic**

1. Declare a JavaScript object named `company` containing:
   - `name`: a string (e.g. `"TechCorp"`).
   - `employees`: an array containing at least 3 employee objects, where each object has:
     - `name` (e.g. `"Alice"`, `"Bob"`, `"Charlie"`)
     - `role` (e.g. `"Developer"`, `"Designer"`, `"Manager"`)
2. Define a function named `showInfo()` that runs when the button is clicked:
   - Show the company name in a popup `alert()` (e.g., `Company Name: TechCorp`).
   - Loop through the `employees` array and log each employee's name and role to the console using `console.log()` matching the format:
     `Name: Alice, Role: Developer`

## Test Your Code

Make sure you are in the `student-object` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/15/student-object
```

## Submit Your Code

Make sure you are in the `student-object` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/15/student-object
```
