---
title: Find Customers Starting with J
---

# Find Customers Starting with J

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir j-customers` to create a folder called `j-customers`
- write `cd j-customers` to go to the `j-customers` folder
- download the datasets:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/j-customers/CUSTOMERS.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/j-customers/ORDERS.csv
  ```
- create the sqlite database file and load the tables:
  ```bash
  sqlite3 store.db
  ```
  Inside sqlite, run:
  ```sql
  .mode csv
  .import CUSTOMERS.csv CUSTOMERS
  .import ORDERS.csv ORDERS
  .exit
  ```
- write `code j-customers.sql` to create a file called `j-customers.sql` and open it in the editor

## Problem
In `j-customers.sql`, write a SQL query to retrieve all customer details for customers whose `first_name` starts with the letter `'J'`.

Your query should run on a database `store.db` that contains a table `CUSTOMERS` with columns:
- `customer_id`
- `first_name`
- `last_name`
- `age`
- `country`

## Example Output
When run on the default dataset, your query should output:

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>1|John|Doe|31|USA
2|Jane|Smith|25|UK
3|Jack|Ma|48|China
5|James|Bond|35|UK</code></pre></div></div>

## How to Test
To test your query manually, run it against the database:

```bash
sqlite3 store.db < j-customers.sql
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/11/j-customers
```

## Submit Your Code
Make sure you are in the `j-customers` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/11/j-customers
```
