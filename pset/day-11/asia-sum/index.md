---
title: Asia Sum
---

# E. Asia Sum

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir asia-sum` to create a folder called `asia-sum`
- write `cd asia-sum` to go to the `asia-sum` folder
- download the data files by running:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/8/asia-sum/CITY.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/8/asia-sum/COUNTRY.csv
  ```
- create the SQLite database and import the data:
  ```bash
  sqlite3 cities.db
  ```
  *(Note: If the terminal asks `Are you sure you want to create cities.db? [y/N]`, type `y` and press Enter).*

  Then inside the `sqlite3` prompt:
  ```sql
  .mode csv
  .import CITY.csv CITY
  .import COUNTRY.csv COUNTRY
  .quit
  ```
- write `code asia-sum.sql` to create a file called `asia-sum.sql` and open it in the editor

## Problem

Given the `CITY` and `COUNTRY` tables, query the sum of the populations of all cities where the `CONTINENT` is `'Asia'`.

Note: `CITY.COUNTRYCODE` and `COUNTRY.CODE` are matching key columns.

## Input Format

The `CITY` and `COUNTRY` tables are described as follows:

**CITY**

| Field | Type |
|-------|------|
| ID | NUMBER |
| NAME | VARCHAR2(17) |
| COUNTRYCODE | VARCHAR2(3) |
| DISTRICT | VARCHAR2(20) |
| POPULATION | NUMBER |

**COUNTRY**

| Field | Type |
|-------|------|
| CODE | VARCHAR2(3) |
| NAME | VARCHAR2(44) |
| CONTINENT | VARCHAR2(13) |
| CAPITAL | VARCHAR2(35) |
| AREA | NUMBER |
| POPULATION | NUMBER |

## Example Output

```text
311021451
```

## Test Your Code

Make sure you are in the `asia-sum` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/pset/11/asia-sum
```

## Submit Your Code

Make sure you are in the `asia-sum` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/11/asia-sum
```
