# Intro

Welcome to the Power BI track of this GitHub Copilot upskilling course.

## What these exercises are about

These exercises are a Power BI-focused version of the core Copilot learning path.
You will practice how to use Copilot to:

- generate and refine DAX measures
- work in semantic model files (`.tmdl`)
- fix logic bugs in model calculations
- use slash commands and workspace search for faster model development
- apply better collaboration patterns for pull requests and review

The progression goes from easy starter tasks to more realistic semantic modeling scenarios.

## What the data is about

The dataset represents a fictional sales domain and includes business entities such as:

- sales orders (fact-level transactions)
- products
- customers
- regions and dates

It is designed to support common analytics questions like revenue, margin, YTD performance, and ranking.

## What the data model is about

The model follows a star-schema style pattern:

- `Sales` as the main fact table
- `Products` and `Customers` as dimension tables
- relationships from dimensions to fact

This structure helps learners practice realistic DAX behavior around row context, filter context, and cross-table calculations.

## Prerequisite (important)

Install a TMDL extension in VS Code so the editor can understand and highlight what you create in `.tmdl` files.

Without TMDL support, editing model files is harder and Copilot suggestions are less reliable.
