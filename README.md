# Type Coercion Bug in JavaScript

This repository demonstrates a common type coercion bug in JavaScript.  The `foo` function is intended to add two numbers, but due to type coercion, it performs string concatenation when one of the inputs is a string.

## Bug
The `bug.js` file contains the buggy code.  The `foo` function incorrectly adds a number and a string, resulting in string concatenation.

## Solution
The `bugSolution.js` file provides a corrected version of the `foo` function. The solution uses `parseInt()` or `Number()` to explicitly convert the string to a number before performing the addition. This ensures correct numerical addition.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` and observe the unexpected output.
3. Open `bugSolution.js` to see how to correct the bug using type checking or explicit conversion.