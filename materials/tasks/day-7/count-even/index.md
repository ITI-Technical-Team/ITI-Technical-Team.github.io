---
title: Count Even Numbers
---

# Count Even Numbers

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir count-even` to create a folder called `count-even`
- write `cd count-even` to go to the `count-even` folder
- write `code count-even.cpp` to create a file called `count-even.cpp` and open it in the editor

## Problem
Write a program that reads an array of integers from the user and counts how many of them are even numbers. The counting logic must be implemented inside a custom function with the following signature:
`int countEvenNumbers(int arr[], int size)`

The program should:
1. Read the number of elements `N` from standard input.
2. Read the `N` array elements from standard input.
3. Call the `countEvenNumbers` function to count the even numbers.
4. Print the total count to standard output.

## Example
Here is how the program should run. Inputs typed by the user are shown in **bold**.

```text
$ ./count-even
**5**
**1 7 7 15 10**
1
```

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make count-even
./count-even
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/7/count-even
```

## Submit Your Code
Make sure you are in the `count-even` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/7/count-even
```
