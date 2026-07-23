---
title: Calculate Total Spent
---

# Calculate Total Spent

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir total-spent` to create a folder called `total-spent`
- write `cd total-spent` to go to the `total-spent` folder
- download the datasets:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/total-spent/CUSTOMERS.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/total-spent/ORDERS.csv
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
- write `code total-spent.sql` to create a file called `total-spent.sql` and open it in the editor

## Problem
In `total-spent.sql`, write a SQL query to find the total amount spent by each customer (by `customer_id`). Only show customers who have spent a total of more than `500`.

Your query should output two columns: `customer_id` and the total sum of their order amounts.

Your query should run on a database `store.db` that contains a table `ORDERS` with columns:
- `order_id`
- `customer_id`
- `amount`
- `item`

## Example Output
When run on the default dataset, your query should output:

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>1|650.0
2|950.0
3|1200.0
4|1300.0
6|600.0</code></pre></div></div>

## How to Test
To test your query manually, run it against the database:

```bash
sqlite3 store.db < total-spent.sql
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/11/total-spent
```

## Submit Your Code
Make sure you are in the `total-spent` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/11/total-spent
```
