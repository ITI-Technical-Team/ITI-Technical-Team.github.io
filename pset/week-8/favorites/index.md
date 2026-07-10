---
title: Favorites
---

# B. Favorites

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir favorites` to create a folder called `favorites`
- write `cd favorites` to go to the `favorites` folder
- download the data file by running:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/8/favorites/favorites.csv
  ```
- write `code favorites.py` to create a file called `favorites.py` and open it in the editor

## Problem

You are given a CSV file called `favorites.csv`, which contains data about people's favorite CS problems. Each row has a column labeled `problem`, which stores the name of a specific problem. Your task is to:

- Ask the user to input the name of a problem (case-sensitive)
- Count how many people have selected that problem as their favorite
- Return the count of votes for the given problem. If the problem is not found, display a message stating that the problem is not in the data.

## Example

**Input:**

```text
Enter the name of a problem: Cash
```

**Output:**

```text
Cash received 24 votes.
```

## Test Your Code

Make sure you are in the `favorites` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/pset/8/favorites
```

## Submit Your Code

Make sure you are in the `favorites` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/8/favorites
```
