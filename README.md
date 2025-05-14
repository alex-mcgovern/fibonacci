# Fibonacci Sequence Generator

A Python implementation of functions to generate Fibonacci numbers and sequences.

## Overview

This project provides two main functions:
- `fibonacci(n)`: Returns the nth Fibonacci number
- `fibonacci_sequence(length)`: Generates a list of Fibonacci numbers up to the specified length

## Usage

```python
from fibonacci import fibonacci, fibonacci_sequence

# Generate a single Fibonacci number
nth_number = fibonacci(5)

# Generate a sequence of Fibonacci numbers
sequence = fibonacci_sequence(10)
print(f"First 10 Fibonacci numbers: {sequence}")
```

## Function Documentation

### fibonacci(n)
Returns the nth Fibonacci number (0-indexed).

**Parameters:**
- `n` (int): The position in the Fibonacci sequence

**Returns:**
- `int`: The nth Fibonacci number

**Note:**
- fibonacci(0) = 0
- fibonacci(1) = 1
- fibonacci(n) = fibonacci(n-1) + fibonacci(n-2) for n > 1

### fibonacci_sequence(length)
Generates a list containing the Fibonacci sequence of the specified length.

**Parameters:**
- `length` (int): Number of elements to generate

**Returns:**
- `list`: A list of Fibonacci numbers

**Raises:**
- `ValueError`: If length is negative