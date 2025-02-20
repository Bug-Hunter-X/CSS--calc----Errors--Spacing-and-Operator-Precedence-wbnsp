# CSS calc() Errors: Spacing and Operator Precedence

This repository demonstrates two uncommon errors that can occur when using the `calc()` function in CSS: incorrect spacing and incorrect operator precedence.

## Bug 1: Incorrect Spacing
Incorrect spacing between operators and operands in the `calc()` function can cause unexpected results.  For example:

```css
/* Incorrect spacing causes unexpected behavior */
width: calc(100% - 20px);
```

## Bug 2: Incorrect Operator Precedence
Using multiple operators in a `calc()` expression requires care with operator precedence.  Unexpected results can occur without proper use of parentheses:

```css
/* Incorrect precedence causes unexpected behavior */
height: calc(20px + 100% * 2);
```

## Solutions
The `bugSolution.css` file provides solutions to these problems by correctly spacing operands and using parentheses to ensure correct operator precedence.

## How to Run
1. Clone this repository.
2. Open the `bug.html` (or equivalent file that references the CSS)  and `bugSolution.html` files in your browser.