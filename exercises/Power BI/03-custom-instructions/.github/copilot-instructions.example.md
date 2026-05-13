# Copilot Instructions for Power BI Semantic Modeling

Use these instructions for all Power BI-related suggestions in this workspace.

## Modeling priorities

- Prefer a star schema mindset in examples.
- Propose measures (not calculated columns) unless explicitly asked otherwise.
- Keep business logic in measures and keep measure names business-readable.

## DAX style

- Use `VAR` blocks for intermediate expressions when a formula is non-trivial.
- Prefer `DIVIDE(numerator, denominator)` over `/`.
- For time intelligence, mention assumptions about date table/date column.
- Explain filter context changes when using `CALCULATE`.

## Quality and maintainability

- Suggest measure descriptions/comments when helpful.
- Flag potential performance risks (large iterators, repeated expression evaluation).
- If requirements are ambiguous, provide 1-2 candidate measures and explain trade-offs.

## Naming

- Use title case for measures (example: `Total Revenue`).
- Use concise technical names for helper measures (example: `_Base Revenue`).
