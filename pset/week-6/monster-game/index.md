---
title: Monster Game
---

# C. Monster Game

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir monster-game` to create a folder called `monster-game`
- write `cd monster-game` to go to the `monster-game` folder
- write `code monster-game.cpp` to create a file called `monster-game.cpp` and open it in the editor

## Problem

Now you will play the **Monster — Game.**

You are given an integer \\(h\\), which is your health.

And you are given an array of \\(n\\) integers called \\(A\\), which is the health of \\(n\\) monsters you will fight.

For each monster, if your health is greater than its health, you will defeat it; otherwise, you will skip that monster to avoid a loss.

Your task is to count how many monsters you can defeat and print the answer.

## Input

First line has one integer \\(h\\) : your health, (\\(1 \\leq h \\leq 100\\)).

Second line has one integer \\(n\\) : number of monsters, (\\(1 \\leq n \\leq 100\\)).

Third line has \\(n\\) integers (Array \\(A\\)) : monsters health, (\\(1 \\leq A_i \\leq 100\\)).

## Output

Print one integer that denotes the number of monsters you can defeat.

## Example

**Input:**

```text
10
5
8 3 12 4 16
```

**Output:**

```text
3
```

## Note

In the given example, you can defeat \\(1^{st}\\), \\(2^{nd}\\), and \\(4^{th}\\) monsters, because your health is greater than their health.

## Test Your Code

Make sure you are in the `monster-game` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/6/monster-game
```

## Submit Your Code

Make sure you are in the `monster-game` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/6/monster-game
```
