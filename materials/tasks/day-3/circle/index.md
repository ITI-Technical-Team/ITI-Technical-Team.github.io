---
title: Circle Properties
---

# Circle Properties

Implement a program that takes the **radius** of a circle from the user and calculates its area and perimeter. Assume $\pi = 3.14$.

* **Area** $= \pi \times R \times R$
* **Perimeter** $= 2 \times \pi \times R$

## Example Run

Your program should output the prompt `Radius = ` before reading the input.

```text
Radius = 2.0
Area = 12.56
Perimeter = 12.56
```

## Setup

Create a directory named `circle` on your system and create a file named `circle.cpp` inside it.

```bash
mkdir circle
cd circle
code circle.cpp
```

Write your C++ program in `circle.cpp`.

## Testing

You can test your program manually by compiling and running it:

```bash
g++ -o circle circle.cpp
./circle
```

Or you can use `check50` to test your code automatically:

```bash
check50 iti-technical-team/problemset/pset/lec/3/circle
```

## Submission

Submit your solution using `submit50`:

```bash
submit50 iti-technical-team/problemset/pset/lec/3/circle
```
