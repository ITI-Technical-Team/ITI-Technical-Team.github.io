---
title: Display Customer Orders
---

# Display Customer Orders

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir customer-orders` to create a folder called `customer-orders`
- write `cd customer-orders` to go to the `customer-orders` folder
- download the datasets:
  ```bash
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/customer-orders/CUSTOMERS.csv
  wget https://raw.githubusercontent.com/ITI-Technical-Team/Problemset/pset/lec/11/customer-orders/ORDERS.csv
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
- write `code customer-orders.sql` to create a file called `customer-orders.sql` and open it in the editor

## Problem
In `customer-orders.sql`, write a SQL query to display the customer's `first_name`, `last_name`, the `item` they ordered, and the order `amount`.

Your query will require joining the `CUSTOMERS` and `ORDERS` tables on `customer_id`.

Your query should run on a database `store.db` that contains two tables:
- `CUSTOMERS` with columns: `customer_id`, `first_name`, `last_name`, `age`, `country`
- `ORDERS` with columns: `order_id`, `customer_id`, `amount`, `item`

## Example Output
When run on the default dataset, your query should output:

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>John|Doe|Book|250.0
John|Doe|Laptop|400.0
Jane|Smith|Phone|150.0
Jane|Smith|TV|800.0
Jack|Ma|Car|1200.0
Sarah|Connor|Keyboard|300.0
Sarah|Connor|Monitor|1000.0
James|Bond|Headphones|100.0
Maria|Garcia|Camera|600.0</code></pre></div></div>

## How to Test
To test your query manually, run it against the database:

```bash
sqlite3 store.db < customer-orders.sql
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/11/customer-orders
```

## Submit Your Code
Make sure you are in the `customer-orders` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/11/customer-orders
```
