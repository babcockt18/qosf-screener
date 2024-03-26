### QOSF Screening Task: Find Numbers Less Than k using Grover's Algorithm

This repository contains an implementation of a quantum algorithm to find numbers less than `k` within a list of integers using Grover's search algorithm and the PennyLane library.

## Problem Statement

Given a positive integer `k` and a list of integers `list_n`, find the numbers within `list_n` that are less than `k`.

## Implementation

The code consists of two main functions:

1. `oracle(k, list_n)`: Encodes the problem of finding numbers less than `k` in `list_n`.
2. `less_than_k(k, list_n)`: Implements Grover's search algorithm to find numbers less than `k` in `list_n`.

## Example Usage

```python
A = less_than_k(7, [4, 9, 11, 14, 1, 13, 6, 15])
print(A[0])
```

Output:
```
"[4, 1, 6]"
```

## References

1. Deutsch, David, and Richard Jozsa. "Rapid solution of problems by quantum computation." Proceedings of the Royal Society of London. Series A: Mathematical and Physical Sciences 439.1907 (1992): 553-558.
2. Bernstein, Ethan, and Umesh Vazirani. "Quantum complexity theory." SIAM Journal on computing 26.5 (1997): 1411-1473.
3. Grover, Lov K. , "A fast quantum mechanical algorithm for database search", Proceedings of the 28th Annual ACM Symposium on the Theory of Computing (1996), arXiv:quant-ph/9605043.

## License

This project is licensed under the [MIT License](LICENSE).
