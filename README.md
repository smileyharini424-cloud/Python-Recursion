# Python Recursion

## Explanation

Recursion is a programming technique in which a function calls itself to solve a problem.

A recursive function must have a **base case** to stop the recursive calls.

## Problem Statement

Write a Python program to calculate the factorial of a number using recursion.

## Features

* Demonstrates recursive functions
* Uses a base case
* Calculates factorial
* Accepts input from the user
* Demonstrates repeated function calls

## How It Works

The factorial of a number `n` is:

```text
n! = n × (n - 1) × (n - 2) × ... × 1
```

The recursive function follows:

```text
factorial(n) = n × factorial(n - 1)
```

The base case is:

```text
factorial(0) = 1
```

## Technologies Used

* Python 3

## Program Flow

1. Start the program.
2. Read a number from the user.
3. Call the recursive `factorial()` function.
4. Check the base case.
5. Continue recursive calls until the base case is reached.
6. Return the calculated result.
7. Display the factorial.
8. End the program.

## Sample Input

```text id="u7q3mx"
Enter a number: 5
```

## Sample Output

```text id="p4n8vk"
Factorial: 120
```

## Key Learning

* Understanding recursion
* Creating recursive functions
* Using a base case
* Understanding recursive function calls
* Calculating factorial using recursion

## File Location

```text id="k6w2rs"
Python-Recursion/recursion.py
```

## Repository Structure

```text id="m9c5ht"
Python-Recursion/
│
├── recursion.py
└── README.md
```

## Author

V.Harini
