---
title: Retrieve USA Customers
---

# Retrieve USA Customers

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir usa-customers` to create a folder called `usa-customers`
- write `cd usa-customers` to go to the `usa-customers` folder
- download the datasets:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/usa-customers/CUSTOMERS.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/usa-customers/ORDERS.csv
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
- write `code usa-customers.sql` to create a file called `usa-customers.sql` and open it in the editor

## Problem
In `usa-customers.sql`, write a SQL query to retrieve the `first_name` and `age` for all customers who are from the `'USA'`.

Your query should run on a database `store.db` that contains a table `CUSTOMERS` with columns:
- `customer_id`
- `first_name`
- `last_name`
- `age`
- `country`

## Example Output
When run on the default dataset, your query should output:

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>John|31
Sarah|40</code></pre></div></div>

## How to Test
To test your query manually, run it against the database:

```bash
sqlite3 store.db < usa-customers.sql
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/11/usa-customers
```

## Submit Your Code
Make sure you are in the `usa-customers` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/11/usa-customers
```
