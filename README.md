# CSS calc() with percentages and min-content unexpected behavior

This repository demonstrates a subtle bug related to unexpected behavior when using the `calc()` function in CSS, specifically when combining percentages with the `min-content` keyword.

The `bug.css` file contains the problematic code. The `bugSolution.css` file offers a workaround for more consistent behavior across browsers.

## Problem
The problem arises from the interaction between the percentage calculation and the `min-content` value in the `calc()` function.  The actual rendered width often deviates from the expected calculation, resulting in inconsistencies across browsers.

## Solution
The provided solution in `bugSolution.css` uses a different approach to achieve a similar layout. This might involve using `flex-shrink` and `flex-grow` properties to provide more control and predictable behavior.

## Contributing
Feel free to contribute if you find additional insights or alternative solutions.