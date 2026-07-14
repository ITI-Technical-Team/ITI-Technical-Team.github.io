---
title: Continent Average
---

# D. Continent Average

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir continent-avg` to create a folder called `continent-avg`
- write `cd continent-avg` to go to the `continent-avg` folder
- download the data files by running:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/8/continent-avg/CITY.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/8/continent-avg/COUNTRY.csv
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
- write `code continent-avg.sql` to create a file called `continent-avg.sql` and open it in the editor

## Problem

Given the `CITY` and `COUNTRY` tables, query the names of all the continents (`COUNTRY.CONTINENT`) and their respective average city populations (`CITY.POPULATION`) rounded down to the nearest integer.

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
Africa|4929564
Asia|11107908
Europe|2381392
North America|3677587
Oceania|2986495
South America|5674159
```

## Test Your Code

Make sure you are in the `continent-avg` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/pset/11/continent-avg
```

## Submit Your Code

Make sure you are in the `continent-avg` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/11/continent-avg
```
