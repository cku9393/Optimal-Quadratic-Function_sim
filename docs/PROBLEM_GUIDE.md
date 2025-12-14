# BOJ 28164 – Problem-Solving Notes

## Repository status
- Current files: minimal README with problem link, no implementation yet.
- Internet access to BOJ may be restricted (HTTP 403 encountered while fetching the statement from this environment). Copy the official statement locally before coding if you have access.

## Suggested workflow
1. Obtain the problem statement for BOJ 28164 (save a copy under `docs/` if permitted).
2. Draft the algorithm summary and complexity analysis in this file or the README.
3. Implement the solution in `main.py` using Python 3 and only standard library modules.
4. Add sample input/output cases from the statement as quick regression tests (e.g., a simple script under `tests/` or docstring examples).
5. Update the top-level README with run instructions once code exists.

## Implementation checklist
- Parse input via `sys.stdin.readline` for performance.
- Keep the solution deterministic and avoid floating-point unless the statement requires it.
- Add inline comments explaining any non-obvious math or data-structure choices.
- Verify edge cases described in the statement (boundaries, empty sets, etc.).

## Notes about this environment
- Network access to the problem page returned `403 Forbidden`; manual statement capture may be needed.
- No existing build or test tooling is configured; keep scripts runnable with `python3 main.py < input.txt`.
- For response/PR structure and planning expectations, refer to `docs/AGENT_WORKFLOW.md` (constraint ordering, risk checks, plan vs. code mode) derived from the provided workflow resources; some external links were inaccessible (HTTP 403), so guidance is based on available material.
