# Exercise 03 (Power BI) - Custom Instructions

**Time:** ~10 minutes  
**Goal:** Configure Copilot instructions for Power BI semantic modeling workflows.

---

## Background

This mirrors Exercise 03, but your conventions are model-first:

- DAX naming standards
- measure foldering/display folders
- handling of filter context explanations
- performance-aware patterns (variables, iterator caution)

---

## Steps

### 1. Copy the template

Copy:

- `.github/copilot-instructions.example.md`

To:

- `.github/copilot-instructions.md`

### 2. Customize at least two rules

Examples:

- Always create base measures before derived measures.
- Prefer `DIVIDE` over `/` for safe division.
- Include business-friendly measure descriptions.
- Use explicit table prefixes in measure references when clarity improves readability.

### 3. Test before/after behavior

Ask Copilot:

- "Write a DAX measure for average selling price."
- "Write a quick DAX measure using / for division."

Check whether Copilot follows your rules.

### 4. Reflection prompt

Ask:

- "What semantic-modeling conventions should I follow in this repo?"

---

## Done?

Move on to **Exercise 04 (Power BI)**.
