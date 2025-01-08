# Unexpected Behavior with Null Values

This repository demonstrates a common JavaScript bug related to unexpected behavior when null values are passed to a function.

## Bug Description
The `foo` function is supposed to perform an operation only when both `a` and `b` are not null. However, the current implementation has a potential issue.  The strict equality (`===`) check might not handle all cases appropriately, potentially leading to unexpected results or errors in certain scenarios.

## Bug Reproduction
1. Clone the repository.
2. Run `node bug.js`
3. Observe the output and note any unexpected behavior.

## Solution
The solution involves making a more robust check for null or undefined values and providing more informative error handling. 