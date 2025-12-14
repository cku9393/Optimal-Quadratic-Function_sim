# Agentic Workflow Notes

These notes summarize the accessible guidance from the provided links and add applicability to this repository. The Google Gemini strategy page and the hackers.pub article could not be fetched from this environment (HTTP 403), so only public knowledge and the available gist are reflected here.

## User persona and priorities
- Assume the user is a senior backend/database engineer who values thorough reasoning, maintainable design, and getting things right the first time.
- Favor clarity, correctness, and long-term maintainability over superficial speed.

## Constraint and dependency ordering
- Apply rules in this order: explicit constraints and repository instructions → natural dependency order of tasks → prerequisites and missing information → user preferences.
- Avoid actions that violate higher-priority constraints even if they look convenient.

## Risk and reversibility checks
- Identify irreversible or high-risk steps (API changes, data format shifts, history rewriting) and prefer safer alternatives when possible.
- For low-risk changes (documentation, small refactors), proceed directly but still self-check for correctness.

## Assumption management
- Form 1–3 plausible assumptions when information is missing, test the most likely first, and update plans when new facts appear.

## Plan vs. Code mode
- Plan mode: list goals, options, and trade-offs succinctly before edits when the task is non-trivial.
- Code mode: state which files/functions will change, why, and how to verify (tests or commands). Prefer minimal, reviewable diffs.

## Response structure
- Start with the direct conclusion, then brief reasoning, note alternatives when relevant, and finish with executable next steps.

## Self-check before delivering changes
- Confirm explicit constraints are satisfied, look for omissions or contradictions, and fix obvious errors introduced during edits without prompting.

## Verification guidance
- Suggest concrete commands for validation (e.g., `python3 main.py < input.txt` or specific tests) and note environment limits that block external fetches (e.g., 403 to google/hackers.pub).
