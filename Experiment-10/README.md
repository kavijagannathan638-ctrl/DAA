# Experiment 10

## Aim

To analyze and compare the efficiency of Deterministic Quick Sort (DQS) vs. Randomized Quick Sort (RQS) across various input distributions (Random, Sorted, Reverse, and Nearly Sorted).

## Algorithms

- Deterministic Quick Sort (using last element as pivot, with iterative manual stack implementation to prevent stack overflow on worst-case arrays)
- Randomized Quick Sort (using random pivot selection)
- Hoare/Lomuto partitioning scheme

## Result

The execution results show that for Sorted and Reverse arrays, Deterministic Quick Sort degrades to its worst-case complexity $O(n^2)$ (requiring 12,497,500 comparisons and taking ~2 seconds). In contrast, Randomized Quick Sort avoids this worst-case behavior, maintaining $O(n \log n)$ complexity (requiring only ~70,000 comparisons and taking ~20 milliseconds).
