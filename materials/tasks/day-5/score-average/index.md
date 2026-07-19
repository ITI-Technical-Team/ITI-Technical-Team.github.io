---
title: Score Average
---

# Score Average

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir score-average` to create a folder called `score-average`
- write `cd score-average` to go to the `score-average` folder
- write `code score-average.cpp` to create a file called `score-average.cpp` and open it in the editor

## Problem
Write a program that takes scores from the user, stores them in an array, and calculates their average using a custom average function (for example, `double avg(double arr[], int n)` or similar).

**Note:**
1. Get the number of elements `N` from the user (do not hardcode it as a constant).
2. Use a custom function (other than `main`) to calculate the average.
3. The final result must be a floating-point number formatted to exactly 2 decimal places.

## Example

Here is how the program should run in the terminal. The inputs typed by the user are shown in **bold**.

```text
$ ./score-average
Enter the number of elements : **5**
Enter element number 1 : **5**
Enter element number 2 : **1**
Enter element number 3 : **15**
Enter element number 4 : **2**
Enter element number 5 : **10**
average of scores : 6.60
```

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make score-average
./score-average
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/5/score-average
```

## Submit Your Code
Make sure you are in the `score-average` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/5/score-average
```
