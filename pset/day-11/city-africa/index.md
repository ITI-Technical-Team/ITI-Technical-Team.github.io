---
title: City Africa
---

# C. City Africa

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir city-africa` to create a folder called `city-africa`
- write `cd city-africa` to go to the `city-africa` folder
- download the data files by running:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/11/city-africa/CITY.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/11/city-africa/COUNTRY.csv
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
- write `code city-africa.sql` to create a file called `city-africa.sql` and open it in the editor

## Problem

Given the `CITY` and `COUNTRY` tables, query the names of all cities where the `CONTINENT` is `'Africa'`.

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
Cairo
Alexandria
Giza
Lagos
...
```

## Test Your Code

Make sure you are in the `city-africa` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/pset/11/city-africa
```

## Submit Your Code

Make sure you are in the `city-africa` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/11/city-africa
```
