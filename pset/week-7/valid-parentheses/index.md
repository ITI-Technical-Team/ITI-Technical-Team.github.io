---
title: Valid Parentheses
---

# F. Valid Parentheses

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir valid-parentheses` to create a folder called `valid-parentheses`
- write `cd valid-parentheses` to go to the `valid-parentheses` folder
- write `code valid-parentheses.cpp` to create a file called `valid-parentheses.cpp` and open it in the editor

## Problem

You are given a string \\(s\\) consisting of only the characters '(' and ')'. Your task is to determine whether the string represents a valid sequence of parentheses.

**A sequence is considered valid if:**

Every opening bracket '(' has a corresponding closing bracket ')'.

A closing bracket ')' never appears before its matching opening bracket '('.

## Input

The first line contains an integer \\(t (1 \\leq t \\leq 100)\\) — the number of test cases.

Each test case consists of a single line containing the string \\(s (1 \\leq \|s\| \\leq 10^5)\\), which is composed only of '(' and ')'.

## Output

For each test case, print "YES" if the string is a valid balanced sequence; otherwise, print "NO".

## Examples

**Input:**

```text
3
()
((
())(
```

**Output:**

```text
YES
NO
NO
```

**Input:**

```text
4
)()(())
()(((()
(((())))
(())(()))
```

**Output:**

```text
NO
NO
YES
YES
```

## Test Your Code

Make sure you are in the `valid-parentheses` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/7/valid-parentheses
```

## Submit Your Code

Make sure you are in the `valid-parentheses` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/7/valid-parentheses
```
