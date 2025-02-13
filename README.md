# MongoDB $inc Operator Unexpected Behavior

This repository demonstrates an uncommon bug related to the `$inc` operator in MongoDB.  Specifically, it highlights the issue of using a negative increment without proper checks, leading to potential counter problems. The example shows how to reproduce the bug and includes a solution.

## Bug

The `bug.js` file demonstrates how using `$inc` with a negative value without prior existence check can lead to negative counter values or unexpected behavior if the counter doesn't exist.

## Solution

The `bugSolution.js` file provides a corrected approach to handle `$inc` operations reliably and prevents errors in the counter values.