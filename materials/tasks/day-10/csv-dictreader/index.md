---
title: Count Languages with DictReader
---

# Count Languages with DictReader

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir csv-dictreader` to create a folder called `csv-dictreader`
- write `cd csv-dictreader` to go to the `csv-dictreader` folder
- download the dataset file by running the following command:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/10/favorites/favorites.csv
  ```
- write `code csv-dictreader.py` to create a file called `csv-dictreader.py` and open it in the editor

## Problem
Write a Python script to count language frequencies using `csv.DictReader`.

The script should:
1. Open the file `favorites.csv` in read mode.
2. Read the CSV data using `csv.DictReader`.
3. Create an empty dictionary named `counts` to track how many times students selected each programming language as their favorite.
4. Populate `counts` by iterating over the rows and incrementing the count for the language in `row["language"]`.
5. Print the populated dictionary.

## Example
Here is how the program should run.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ python3 csv-dictreader.py
{'Python': 280, 'Scratch': 40, 'C': 78}</code></pre></div></div>

## How to Test
To test your program manually, run it in the terminal:

```bash
python3 csv-dictreader.py
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/10/csv-dictreader
```

## Submit Your Code
Make sure you are in the `csv-dictreader` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/10/csv-dictreader
```
