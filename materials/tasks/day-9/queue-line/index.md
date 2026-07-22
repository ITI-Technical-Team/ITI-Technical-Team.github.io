---
title: Simulate a Line of People (Queue)
---

# Simulate a Line of People (Queue)

## Problem Setup
- login to [CS50 IDE](https://cs50.dev)
- write `cd` in the *terminal* to go to the home directory
- write `mkdir queue-line` to create a folder called `queue-line`
- write `cd queue-line` to go to the `queue-line` folder
- write `code queue-line.cpp` to create a file called `queue-line.cpp` and open it in the editor

## Problem
Write a program that simulates a simple line of people using a `std::queue`.

The program should:
1. Initialize a queue of strings.
2. Push three people into the queue in this order: `"Alice"`, `"Bob"`, and `"Charlie"`.
3. Print `"Serving order:"` to standard output.
4. Process and print the names in the queue one by one as they are served (popped from the front).

## Example
Here is how the program should run.

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>$ ./queue-line
Serving order:
Alice
Bob
Charlie</code></pre></div></div>

## How to Test
To test your program manually, compile it with `make` and run it:

```bash
make queue-line
./queue-line
```

To test your code automatically with `check50`, run:

```bash
check50 iti-technical-team/problemset/pset/lec/9/queue-line
```

## Submit Your Code
Make sure you are in the `queue-line` directory, then run the following command:

```bash
submit50 iti-technical-team/problemset/pset/lec/9/queue-line
```
