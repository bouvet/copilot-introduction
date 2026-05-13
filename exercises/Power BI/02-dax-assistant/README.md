# Exercise 02 (Power BI) - DAX Assistant

**Time:** ~10 minutes  
**Goal:** Use Copilot Chat to write production-style DAX measures for a semantic model.

---

## Background

Like the original exercise, your job is to implement measures from business requirements.

In this Power BI version, you draft in `challenges.tmdl` and use `data_model.md` for context.

---

## Steps

### 1. Open the data model

Open `data_model.md` and keep it open.

### 2. Open the challenge file

Open `challenges.tmdl`.

Each challenge describes a requirement followed by an empty measure definition.

### 3. Ask Copilot Chat for each measure

For each challenge, ask Copilot for the measure and paste/refine it in the file.

Example prompt:

- "Write a DAX measure for Total Margin where margin is revenue minus total cost, using the model in data_model.md."

### 4. Validate context understanding

After at least two measures, ask:

- "Explain filter context for these measures and identify where CALCULATE changes it."

---

## What to Try

- Ask Copilot to optimize a measure for readability and maintainability.
- Ask for a version that avoids repeated expressions using variables.

---

## Done?

Compare with `challenges_solution.tmdl`, then move on to **Exercise 03 (Power BI)**.
