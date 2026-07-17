---
title: "B. Fruit Manager"
---

# B. Fruit Manager

## Background

JavaScript arrays come with many built-in methods to add, remove, search, sort, and format elements.

### Array Modifications

- `push(item)`: adds an item to the **end** of the array.
- `unshift(item)`: adds an item to the **beginning** of the array.
- `splice(index, count, newItem)`: replaces `count` elements starting at `index` with `newItem`.
- `includes(item)`: returns `true` if the item is present, otherwise `false`.
- `sort()`: sorts array elements alphabetically in place.
- `reverse()`: reverses the order of elements in place.
- `join(separator)`: converts the array to a single string separated by the given separator.

### String Methods

- `toLowerCase()`: converts a string to lowercase.
- `toUpperCase()`: converts a string to uppercase.

### Position Logging with forEach

You can iterate through an array with a `forEach` loop and receive both the item and its index:

```javascript
fruits.forEach((fruit, index) => {
    console.log(`${index + 1} - ${fruit.toUpperCase()}`);
});
```

## Problem Setup

- Login to [CS50 IDE](https://cs50.dev)
- In the terminal, run:
  ```bash
  mkdir array-manager
  cd array-manager
  code index.html
  ```

## Problem

Create a **Fruit Manager** page in `index.html` that prompts the user for a fruit and performs various array transformations.

### Requirements

**HTML Structure**

1. A page title of `Fruit Manager`.
2. A heading `<h1>Fruit Manager</h1>`.
3. A `<script>` tag containing your JavaScript.

**JavaScript Logic**

When the page loads, your script must:
1. Define a variable `fruits` initialized as an array: `["apple", "banana", "cherry"]`.
2. Prompt the user to enter a fruit name: `Enter a fruit name:`.
3. Convert the user's input to lowercase using `.toLowerCase()`.
4. Check if the entered fruit already exists in the `fruits` array using `.includes()`:
   - If it **does exist**, show an alert: `Yes, we already have [fruit].` (where `[fruit]` is the lowercase input).
   - If it **does not exist**, add it to the end of the array using `.push()` and show an alert: `[fruit] has been added to the list.`
5. Use `.splice()` to replace the **second fruit** in the array (index 1) with `"blueberry"`.
6. Use `.unshift()` to add `"grape"` to the **beginning** of the array.
7. Sort the array alphabetically using `.sort()`.
8. Reverse the sorted array using `.reverse()`.
9. Convert the final array to a comma-separated string using `.join(", ")` and display it in an `alert()` (e.g. `Updated Fruit List: grape, cherry, blueberry, apple`).
10. Use an **arrow function inside `.forEach()`** to log each fruit name to the console in uppercase with its 1-based index (e.g., `1 - GRAPE`, `2 - CHERRY`, etc.).

## Test Your Code

Make sure you are in the `array-manager` directory, then run:

```bash
check50 iti-technical-team/problemset/pset/15/array-manager
```

## Submit Your Code

Make sure you are in the `array-manager` directory, then run:

```bash
submit50 iti-technical-team/problemset/pset/15/array-manager
```
