---
name: project-budget
description: >
  Build and track a project budget: cost lines from the task list, real quotes
  instead of guesses, a contingency reserve, the timing of payments, and a simple
  tracker of planned versus actual spending, ready to paste into a spreadsheet.
  Use for any project with money involved (renovation, event, wedding, move,
  equipment, IT project), when someone asks "how much will it cost?" or when
  costs start to slip. Triggers: "budget", "how much will it cost", "cost
  estimate", "track expenses", "budget du projet", "combien ça va coûter",
  "estimation des coûts", "suivi des dépenses", "presupuesto", "cuánto va a
  costar", "control de gastos".
---

# Project budget

Budgets go wrong in two ways: forgotten costs and optimistic guesses. This skill builds the budget from the task list, replaces guesses with quotes, sets a reserve, and tracks the real spending as the project goes.

## When to use

- After `work-breakdown`, before committing money.
- When collecting quotes (`vendor-selection` compares them).
- When spending starts to drift from the plan.

## Inputs

1. The task list and deliverables.
2. Quotes, price lists, receipts already available.
3. The budget limit and how the project is paid for (savings, loan, company budget, grant).

## Method

1. **List the cost lines** from the deliverables: materials, labor and services, fees and permits, equipment, travel, insurance, taxes, and the costs people forget (delivery, waste removal, cleaning, temporary housing, training, subscriptions).
2. **Price each line from a source**: a quote, a catalog price, a past invoice. Mark guesses as estimates and replace them with quotes before committing. Prices change: note the date of each price.
3. **Add a contingency reserve**, sized to the uncertainty of the project, and say where the figure comes from. Large projects overrun often, as Flyvbjerg and Gardner document, so a reserve is planning, not pessimism.
4. **Plan the timing of payments**: deposits, installments, final payments, and when the money must be available.
5. **Set up the tracker**: planned, committed (signed but not paid), paid, and the remaining forecast for each line.
6. **Review it** at each milestone: explain every gap, decide whether to use the reserve, cut scope (`scope-change`) or find more money.

## Output

```markdown
### Budget: <project> (version <n>, <date>)
| Line | Source of the price (quote, date) | Planned | Committed | Paid | Forecast | Gap |
|---|---|---|---|---|---|---|
| Contingency reserve | … | | | | | |
| Total | | | | | | |

### Payment calendar
| Date | What | Amount | Paid from |
|---|---|---|---|
```

## Quality bar

- Every line shows where its price comes from and the date; guesses are labeled.
- The reserve is explicit and justified, never hidden inside the lines.
- The tracker separates planned, committed and paid.
- Taxes, fees and rules come from official sources with the date when they matter.
- Written in the user's language, with the terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Budget | Budget | Presupuesto |
| Quote | Devis | Presupuesto (de un proveedor) |
| Contingency reserve | Provision pour imprévus | Reserva para imprevistos |
| Committed cost | Coût engagé | Coste comprometido |
| Cost overrun | Dépassement de budget | Sobrecoste |
| Payment schedule | Échéancier de paiement | Calendario de pagos |

## Sources

- Flyvbjerg, B., & Gardner, D. (2023). *How Big Things Get Done*. Currency.
- Project Management Institute. (2021). *A Guide to the Project Management Body of Knowledge (PMBOK Guide)* (7th ed.). Project Management Institute.
