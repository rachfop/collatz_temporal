# Collatz Conjecture

The Collatz conjecture transform every positive integer into 1 by the following operation:

- If the number is even, divide it by two.
- If the number is odd, triple it and add one.

```math
{\displaystyle f(n)={\begin{cases}{\frac {n}{2}}&{\text{if }}n\equiv 0{\pmod {2}}\\[4px]3n+1&{\text{if }}n\equiv 1{\pmod {2}}.\end{cases}}}
```

Get started:

```bash
poetry run python run_worker.py
poetry run python run_workflow.py
```

Enter a positive integer.

## Run tests

Use `pytest` to automatically discover and run tests.

- `collatz_activity_test`: tests the `collatz()` function.
