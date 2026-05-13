# Exercise 05 (Power BI) - Skills and Slash Commands

**Time:** ~10 minutes  
**Goal:** Practice Copilot Chat slash commands and `@workspace` using semantic-model assets.

---

## Background

This mirrors the original skills exercise but uses a 3-table TMDL semantic model.

Tables in this exercise:

- `Sales` (fact)
- `Products` (dimension)
- `Customers` (dimension)

| Command | Power BI usage |
|---|---|
| `/explain` | Explain a measure or table definition |
| `/fix` | Correct a broken DAX expression |
| `/doc` | Generate a measure description/comment |
| `/tests` | Generate validation scenarios for a measure |
| `@workspace` | Find measures, columns, and model logic across files |

---

## Steps

### 1. Open the messy model file

Open `messy_semantic_model.tmdl`.

### 2. Use `/explain`

Select one complicated measure and run `/explain`.

### 3. Use `/fix`

Select `Revenue YoY %` and run `/fix`.

Ask Copilot why the original expression is unsafe.

### 4. Use `/tests`

Select `Total Revenue` and run `/tests`.

Ask for edge cases such as zero revenue, missing related dimension values, and filtered contexts.

### 5. Use `@workspace`

Try prompts like:

- `@workspace Where is margin percentage calculated in the Power BI exercises?`
- `@workspace Which files define Total Revenue?`
- `@workspace Which measures in Exercise 05 use Customers or Products tables?`

---

## Done?

You completed the Power BI version of exercises 01-05.
