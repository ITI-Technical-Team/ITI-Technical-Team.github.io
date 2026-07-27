---
title: Odd Numbers
---

# Odd Numbers

## Problem Setup
- Open [Scratch](https://scratch.mit.edu/projects/editor/)
- Follow the instructions below to create your project.
- Once finished, save your project to your computer. Click **File > Save to your computer**. The file should end in `.sb3`.

## Problem
Create a Scratch project where the sprite counts and says the **odd numbers from 1 to 9** (i.e. 1, 3, 5, 7, 9).

### Requirements:
1. Use a **loop block** from the Control category (e.g. `repeat [5]`).
2. Use a **variable** (e.g. `oddNumber`) to keep track of the current number.
3. The **`Set` block** that initializes the variable **must be placed BEFORE (outside) the repeat loop** — not inside it. Placing it inside resets the variable every iteration.
4. Use a **`Change` block** inside the loop to increment the variable by `2` each time.
5. Use a **Say** block to display/print each number.
6. The numbers said must be exactly `1`, `3`, `5`, `7`, and `9` in sequence.

> [!WARNING]
> **Common Mistake:** Do **NOT** place the `Set oddNumber to 1` block **inside** the `repeat` loop. If you do, the variable resets to `1` on every iteration, and the sprite will say `1` five times instead of odd numbers. Always initialize the variable **before** the loop begins.

## Submit Your Code

Please upload your `.sb3` file using the following form:

[Odd Numbers Submission Form](https://submit.cs50.io/upload/iti-technical-team/Problemset/pset/lec/2/odd-numbers)
