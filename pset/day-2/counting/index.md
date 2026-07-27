---
title: "Counting"
---

# Counting

## Problem Setup
- Open [Scratch](https://scratch.mit.edu/projects/editor/)
- Follow the instructions below to create your project.
- Once finished, save your project to your computer. Click **File > Save to your computer**. The file should end in `.sb3`.

## Problem

Create a Scratch project where the sprite counts and says the **even numbers from 2 to 100** (i.e. 2, 4, 6, … 100).

### Requirements:
1. Use a **loop block** (e.g. `repeat [50]`) to repeat the counting.
2. Use a **variable** (e.g. `evenNumber`) to keep track of the current number.
3. The **`Set` block** that initializes the variable **must be placed BEFORE (outside) the repeat loop** — not inside it. Placing it inside resets the variable every iteration.
4. Use a **`Change` block** inside the loop to increment the variable by `2` each time.
5. Use a **Say** block to display/print each even number.
6. The numbers said must be exactly `2`, `4`, `6`, … `100` in sequence.

> [!WARNING]
> **Common Mistake:** Do **NOT** place the `Set evenNumber to 2` block **inside** the `repeat` loop. If you do, the variable resets to `2` on every iteration, and the sprite will say `2` fifty times instead of counting up. Always initialize the variable **before** the loop begins.

## Submit Your Code

Please upload your `.sb3` file using the following form:

[Counting Submission Form](https://submit.cs50.io/upload/iti-technical-team/Problemset/pset/2/counting)
