# Repository Agent Guidelines

This repository currently only contains the problem link for BOJ 28164. Use these notes when implementing or updating the solution.

- Preferred language: Python 3. Keep dependencies to the standard library.
- Entry point: `main.py` at repository root. Provide a `main()` function and guard it with `if __name__ == "__main__":`.
- Keep I/O fast (`sys.stdin.readline`, `sys.stdout.write`) and avoid unnecessary overhead.
- Add short comments describing the algorithm and its complexity.
- Include a brief usage note or sample I/O in the README when you add the solution.
- Tests: include a minimal set of sample cases as doctests or simple assertions in a separate file if feasible. No external test frameworks are required.
- When writing responses or PR descriptions, follow the decision-and-planning workflow summarized in `docs/AGENT_WORKFLOW.md` (priority of constraints, risk checks, plan/code mode separation, and concise verification steps).

If you need to add additional instructions for subdirectories, create nested `AGENTS.md` files there. The scope of this file covers the entire repository.
