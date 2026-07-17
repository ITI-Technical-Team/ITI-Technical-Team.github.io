---
title: Compare Numbers
---

# Compare Numbers

Implement a program that takes two integer variables **X** and **Y** from the user and compares them:
* If $X < Y$, print `X is less than Y`
* If $X > Y$, print `X is greater than Y`
* If $X = Y$, print `X is equal to Y`

## Example Runs

Your program should output the prompts `X = ` and `Y = ` before reading each input.

### Example 1
```text
X = 5
Y = 10
X is less than Y
```

### Example 2
```text
X = 10
Y = 5
X is greater than Y
```

### Example 3
```text
X = 5
Y = 5
X is equal to Y
```

## Setup

Create a directory named `compare-numbers` on your system and create a file named `compare-numbers.cpp` inside it.

```bash
mkdir compare-numbers
cd compare-numbers
code compare-numbers.cpp
```

Write your C++ program in `compare-numbers.cpp`.

## Testing

You can test your program manually by compiling and running it:

```bash
g++ -o compare-numbers compare-numbers.cpp
./compare-numbers
```

Or you can use `check50` to test your code automatically:

```bash
check50 iti-technical-team/problemset/pset/lec/3/compare-numbers
```

## Submission

Submit your solution using `submit50`:

```bash
submit50 iti-technical-team/problemset/pset/lec/3/compare-numbers
```
