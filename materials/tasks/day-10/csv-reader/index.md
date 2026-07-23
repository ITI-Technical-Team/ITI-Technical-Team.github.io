---
title: Read CSV Problem Column
---

# Read CSV Problem Column

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir csv-reader` to create a folder called `csv-reader`
- write `cd csv-reader` to go to the `csv-reader` folder
- download the dataset file by running the following command:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/10/favorites/favorites.csv
  ```
- write `code csv-reader.py` to create a file called `csv-reader.py` and open it in the editor

## Problem
Write a Python script to open `favorites.csv` and read its data using `csv.reader`.

The script should:
1. Open the file `favorites.csv` in read mode.
2. Read the CSV data using `csv.reader`.
3. Print only the `problem` column (the 3rd column, i.e., index `2`) for all rows, skipping the header row.

## Example
Here is how the program should run.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ python3 csv-reader.py
Hello, World
DNA
Hello, World
Scratch
Speller ...</code></pre></div></div>

## How to Test
To test your program manually, run it in the terminal:

```bash
python3 csv-reader.py
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/10/csv-reader
```

## Submit Your Code
Make sure you are in the `csv-reader` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/10/csv-reader
```
