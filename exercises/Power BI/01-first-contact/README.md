# Exercise 01 (Power BI) — First Contact

**Time:** ~10 minutes  
**Goal:** Get comfortable with Copilot inline suggestions and chat using a single, cognitively easy DAX measure.

---

## Background

In this Power BI version, your starter file is a semantic-model table definition in text form (`Sales.tmdl`).

You will complete one very simple measure and ask Copilot to explain it.

---

## Steps

### 1. Open the starter semantic model file

Open `SalesStarter.SemanticModel/definition/tables/Sales.tmdl`.

Find the `Total Revenue` measure with a TODO.

### 2. Use inline completion

Place your cursor after the `=` in `Total Revenue` and start typing:

- `SUMX(`

Accept Copilot's suggestion if it correctly multiplies quantity and unit price row by row.

### 3. Guide Copilot with a comment

Above `Orders Count`, write a short comment like:

- `// count distinct orders`

Press Enter and accept/refine the suggestion.

### 4. Ask Copilot Chat to explain

Highlight `Total Revenue` and ask:

- "Explain this measure in plain language for a business stakeholder."

---

## What to Try

- Ask: "Can you rewrite `Total Revenue` without `SUMX`?"
- Ask: "When should I prefer an explicit iterator in DAX?"

---

## Done?

Compare with `Sales_solution.tmdl`, then move on to **Exercise 02 (Power BI)**.
