---
title: Sort Language Frequencies
---

# Sort Language Frequencies

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir csv-sorted` to create a folder called `csv-sorted`
- write `cd csv-sorted` to go to the `csv-sorted` folder
- download the dataset file by running the following command:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/10/favorites/favorites.csv
  ```
- write `code csv-sorted.py` to create a file called `csv-sorted.py` and open it in the editor

## Problem
Modify your previous code to count language frequencies and print them sorted alphabetically by language name (from A to Z).

The script should:
1. Open the file `favorites.csv` in read mode.
2. Read the CSV data using `csv.DictReader`.
3. Count language frequencies in a `counts` dictionary.
4. Print each language name and its frequency (e.g. `Language: Count`), sorted alphabetically by the language name from A to Z.

## Example
Here is how the program should run.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ python3 csv-sorted.py
C: 78
Python: 280
Scratch: 40</code></pre></div></div>

## How to Test
To test your program manually, run it in the terminal:

```bash
python3 csv-sorted.py
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/10/csv-sorted
```

## Submit Your Code
Make sure you are in the `csv-sorted` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/10/csv-sorted
```
