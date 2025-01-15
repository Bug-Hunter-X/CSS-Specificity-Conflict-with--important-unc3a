# CSS Specificity Conflict with !important

This repository demonstrates a common yet subtle issue in CSS related to specificity and the `!important` flag.  The problem arises when a more specific selector tries to override a rule with `!important` set.  The `!important` flag has higher precedence, resulting in unexpected behavior.

## Bug Description
The bug is a conflict between the specificity of CSS selectors and the use of the `!important` flag.  A more specific selector is unable to override a less specific selector that uses `!important`.

## Solution
The provided solution demonstrates how to resolve this issue using a variety of techniques, including refactoring CSS to eliminate the need for `!important`, using a more specific selector, or strategically incorporating the `!important` flag.

## How to Reproduce
1. Clone the repository
2. Open the `bug.html` file in your browser. Observe the unexpected color.
3. Open the `bugSolution.html` file in your browser and see how the issue is resolved.