# MiniTorch Module 0

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module0/module0/

## Results

All tasks 0.1 - 0.4 are implemented and the full test suite passes in CI
(see `.github/workflows/minitorch.yml`).

| Task | What | Where |
| --- | --- | --- |
| 0.1 | Elementary operators | `minitorch/operators.py` |
| 0.2 | Property tests | `tests/test_operators.py` |
| 0.3 | Higher-order functions | `minitorch/operators.py` |
| 0.4 | `Module` tree | `minitorch/module.py` |

Local run: `43 passed, 1 xfailed` on Python 3.11.

Task 0.5 is the manual-parameter Streamlit visualization, which the course
explicitly allows to skip.
