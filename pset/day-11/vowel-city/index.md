---
title: Vowel City
---

# G. Vowel City

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir vowel-city` to create a folder called `vowel-city`
- write `cd vowel-city` to go to the `vowel-city` folder
- download the data file by running:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/11/vowel-city/STATION.csv
  ```
- create the SQLite database and import the data:
  ```bash
  sqlite3 station.db
  ```
  *(Note: If the terminal asks `Are you sure you want to create station.db? [y/N]`, type `y` and press Enter).*

  Then inside the `sqlite3` prompt:
  ```sql
  .mode csv
  .import STATION.csv STATION
  .quit
  ```
- write `code vowel-city.sql` to create a file called `vowel-city.sql` and open it in the editor

## Problem

Query the list of `CITY` names from `STATION` which have vowels (i.e., *a*, *e*, *i*, *o*, and *u*) as both their first and last characters. Your result cannot contain duplicates.

## Input Format

The `STATION` table is described as follows:

| Field | Type |
|-------|------|
| ID | NUMBER |
| CITY | VARCHAR2(21) |
| STATE | VARCHAR2(2) |
| LAT_N | NUMBER |
| LONG_W | NUMBER |

## Example Output

```text
Abilene
Albuquerque
Alexandria
Alma
Alpine
Anchorage
...
```

## Test Your Code

Make sure you are in the `vowel-city` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/pset/11/vowel-city
```

## Submit Your Code

Make sure you are in the `vowel-city` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/11/vowel-city
```
