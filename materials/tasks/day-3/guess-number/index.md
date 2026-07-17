---
title: Guess Number Type
---

# Guess Number Type

Implement a program that takes a **Guess character** (representing a number's sign) and a **number** (an integer), and determines if the guess is correct or not.

The Guess character can be:
* `'P'` for positive numbers ($> 0$)
* `'N'` for negative numbers ($< 0$)
* `'Z'` for zero ($= 0$)

Print `YES` if the guess is correct, and `NO` otherwise.

## Example Runs

### Example 1
```text
P
5
YES
```

### Example 2
```text
N
-1
YES
```

### Example 3
```text
P
-5
NO
```

### Example 4
```text
Z
0
YES
```

## Setup

Create a directory named `guess-number` on your system and create a file named `guess-number.cpp` inside it.

```bash
mkdir guess-number
cd guess-number
code guess-number.cpp
```

Write your C++ program in `guess-number.cpp`.

## Testing

You can test your program manually by compiling and running it:

```bash
g++ -o guess-number guess-number.cpp
./guess-number
```

Or you can use `check50` to test your code automatically:

```bash
check50 iti-technical-team/problemset/pset/lec/3/guess-number
```

## Submission

Submit your solution using `submit50`:

```bash
submit50 iti-technical-team/problemset/pset/lec/3/guess-number
```
