# TypeScript Bug: Infinite Loop in `printNumbers` Function

This repository demonstrates a common error in TypeScript: an infinite loop caused by improper handling of negative input in a `for` loop.

The `printNumbers` function is intended to print numbers from 1 to `n`. However, when `n` is negative, the loop condition `i <= n` is always true, resulting in an infinite loop.

The solution involves adding a check to ensure `n` is non-negative before starting the loop.