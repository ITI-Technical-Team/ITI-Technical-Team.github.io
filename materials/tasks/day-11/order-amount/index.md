---
title: Filter Orders by Amount
---

# Filter Orders by Amount

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir order-amount` to create a folder called `order-amount`
- write `cd order-amount` to go to the `order-amount` folder
- download the datasets:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/order-amount/CUSTOMERS.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/order-amount/ORDERS.csv
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
- write `code order-amount.sql` to create a file called `order-amount.sql` and open it in the editor

## Problem
In `order-amount.sql`, write a SQL query to find all orders where the `amount` is between `300` and `1000` (inclusive).

Your query should run on a database `store.db` that contains a table `ORDERS` with columns:
- `order_id`
- `customer_id`
- `amount`
- `item`

## Example Output
When run on the default dataset, your query should output:

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>2|1|400.0|Laptop
4|2|800.0|TV
6|4|300.0|Keyboard
7|4|1000.0|Monitor
9|6|600.0|Camera</code></pre></div></div>

## How to Test
To test your query manually, run it against the database:

```bash
sqlite3 store.db < order-amount.sql
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/11/order-amount
```

## Submit Your Code
Make sure you are in the `order-amount` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/11/order-amount
```
