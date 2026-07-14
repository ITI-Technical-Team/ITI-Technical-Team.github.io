---
title: Language Count
---

# A. Language Count

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir language-count` to create a folder called `language-count`
- write `cd language-count` to go to the `language-count` folder
- download the data file by running:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/8/language-count/favorites.csv
  ```
- write `code language-count.py` to create a file called `language-count.py` and open it in the editor

## Problem

Write a Python program that reads a CSV file called `favorites.csv` containing survey results about favorite programming languages. Your program should:

- Count how many times each language appears in the `language` column
- Print the counts in **descending order** of frequency

## Output

```text
Python: 280
C: 78
Scratch: 40
```

## Test Your Code

Make sure you are in the `language-count` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/pset/10/language-count
```

## Submit Your Code

Make sure you are in the `language-count` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/10/language-count
```
