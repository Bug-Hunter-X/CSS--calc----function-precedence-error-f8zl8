# CSS `calc()` function precedence error

This repository demonstrates a subtle error that can occur when using the `calc()` function in CSS.  The issue arises from incorrect operator precedence when combining percentages and fixed pixel values.

## The Problem

The `calc()` function in CSS allows dynamic calculations for property values. However, if you're not careful with operator precedence, unexpected results can occur.  This example shows how subtracting a fixed pixel value from a percentage value can yield an unexpected result due to operator precedence. The subtraction happens before the percentage is calculated from the parent element's width.

## Solution

A simple fix involves using parentheses to ensure the percentage calculation is done before the subtraction. 

## How to run
1. Clone the repository
2. Open `bug.html` in your web browser to see the incorrect results.
3. Open `bugSolution.html` to see the corrected results.

Feel free to contribute or report any issues.