# CSS Specificity Bug

This repository demonstrates a subtle but important bug related to CSS specificity. The bug highlights a situation where the order of selectors in a stylesheet does not directly determine which style is applied, contrary to initial intuition.  Specificity plays a critical role, and understanding it is essential for writing robust and predictable CSS.

## Bug Description

The `bug.css` file contains CSS rules that unexpectedly override each other due to specificity. The expected behavior is not achieved because of the way CSS specificity rules resolve conflicting styles.  The `bugSolution.css` file illustrates a corrected approach.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` (You will need to create a simple HTML file to test this). 
3. Observe the unexpected styling of the targeted element.

## Solution

The solution involves a deeper understanding of CSS specificity and how it resolves selector conflicts. Refer to the comments in `bugSolution.css` for details.