---
title: Queue
---

# E. Queue

## Problem Setup

- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir queue` to create a folder called `queue`
- write `cd queue` to go to the `queue` folder
- write `code queue.cpp` to create a file called `queue.cpp` and open it in the editor

## Problem

You have an empty queue. You need to perform the following queries:

Type 1: Enqueue an integer \\(x\\) to the back of the queue.

Type 2: Dequeue the front element of the queue and print it if the queue is not empty. If the queue is empty, print "Empty!" (without quotes) instead.

## Input

The first line contains a single integer \\(q (1 \\leq q \\leq 10^5)\\) — the number of queries.

Each of the next \\(q\\) lines contains a query. The \\(i\\)-th query is described by two integers \\(t_i\\) and \\(x_i (1 \\leq t_i \\leq 2, 1 \\leq x_i \\leq 10^9)\\) — the type of the query and the integer \\(x_i\\).

## Output

For each query of the second type, print the answer on a separate line.

## Example

**Input:**

```text
5
1 1
1 2
2
2
2
```

**Output:**

```text
1
2
Empty!
```

## Test Your Code

Make sure you are in the `queue` directory, then run the following command:

```bash
check50 iti-technical-team/problemset/2026/7/queue
```

## Submit Your Code

Make sure you are in the `queue` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/2026/7/queue
```
