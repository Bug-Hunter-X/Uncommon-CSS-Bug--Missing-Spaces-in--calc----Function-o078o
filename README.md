# Uncommon CSS Bug: Missing Spaces in `calc()` Function

This repository demonstrates a common yet easily overlooked bug in CSS involving the `calc()` function.  Incorrect spacing within the `calc()` function can lead to unexpected results or parsing errors.  The example provided illustrates the issue and the correct solution.

## Bug Description:

Missing spaces between operators and operands within the `calc()` function in CSS causes unexpected behavior and renders the code invalid. The CSS parser cannot correctly interpret the expression if spaces are missing.

## Solution:

The correct way to use the `calc()` function necessitates adding spaces around operators (+, -, *, /).

## How to Reproduce:

1. Open `bug.css` to see the incorrect implementation of `calc()`. 
2. Open `bugSolution.css` to see the correct implementation of `calc()`.  Notice the inclusion of spaces. 
3. Observe the difference in browser rendering when this CSS is applied to HTML elements.