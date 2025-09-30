# Math Codes — numerical & analytical examples

A public collection of math problems and their code solutions (Python).  
Each problem lives in `problems/<slug>/` and includes a `PROBLEM.md`, implementation, and example runs.

## Contents
- `problems/` — problem folders (problem statement + code)
- `tests/` — unit tests
- `CONTRIBUTING.md` — how to contribute
- `LICENSE` — MIT

## Example: Trapezoidal rule approximation
See `problems/approx_trapezoid/PROBLEM.md` and the implementation at `problems/approx_trapezoid/trapezoidal_rule.py`.

## Quick start
```bash
git clone https://github.com/<your-username>/<repo>.git
cd <repo>
python3 -m venv .venv
source .venv/bin/activate
pip install -r problems/approx_trapezoid/requirements.txt  # if exists
python problems/approx_trapezoid/example_run.py
