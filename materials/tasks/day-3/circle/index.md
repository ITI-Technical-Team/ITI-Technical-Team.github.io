---
title: Circle Properties
---

# Circle Properties

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir circle` to create a folder called `circle`
- write `cd circle` to go to the `circle` folder
- write `code circle.cpp` to create a file called `circle.cpp` and open it in the editor

## Problem
Implement a program that takes the **radius** of a circle from the user and calculates its area and perimeter. Assume $\pi = 3.14$.

Your program should output the prompt `Radius = ` before reading the input.

* **Area** $= \pi \times R \times R$
* **Perimeter** $= 2 \times \pi \times R$

## Example

**Input:**
```
2.0
```

**Output:**
```
Radius = Area = 12.56
Perimeter = 12.56
```

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make circle
./circle
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/3/circle
```

## Submit Your Code
Make sure you are in the `circle` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/3/circle
```
