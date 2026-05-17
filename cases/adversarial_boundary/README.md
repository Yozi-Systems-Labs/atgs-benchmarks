# Adversarial Boundary Cases v1.0

## Purpose

Adversarial boundary cases are designed to test whether ATGS refuses invalid, undefined, degenerate, or numerically unstable inputs correctly.

## Initial Case Families

1. disconnected graph
2. isolated node
3. missing reverse transitions
4. reducible generator
5. near-singular transient block
6. unidirectional entropy request

## Benchmark Principle

ATGS should not silently fabricate finite values where the mathematics is undefined.
