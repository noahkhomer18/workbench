---
name: project-recovery
description: >
  Get a late, over-budget or stuck project back under control: measure the real
  gap, find the causes, compare the recovery options (cut scope, move the date,
  add money or people, change the approach), choose with the decision owner, and
  announce a new credible plan. Use when a project is late, over budget, stuck,
  or when someone asks "how do we save this project?". Triggers: "project is
  late", "behind schedule", "over budget", "rescue the project", "projet en
  retard", "dépassement de budget", "sauver le projet", "le projet dérape",
  "proyecto retrasado", "fuera de presupuesto", "rescatar el proyecto".
---

# Project recovery

A late project rarely recovers by working harder on the same plan. This skill measures the real gap, finds why it happened, and puts honest options in front of the person who decides.

## When to use

- When a milestone slipped or the budget is going beyond its reserve.
- When the people involved no longer believe the plan.
- Not for a single new request that changes the scope: use `scope-change`.

## Inputs

1. The current plan, the budget and what has been done.
2. The latest status (`status-update`) and the risk register.
3. The fixed constraints: dates that cannot move, money that cannot grow.

## Method

1. **Stop and measure**: remaining work re-estimated from scratch by the people doing it, against the time and money left. No "we will catch up".
2. **Find the causes**: underestimated work, scope that grew, missing people or skills, external delays, decisions that were not made. Ask "why" until the cause is something that can be acted on.
3. **List the options**, usually a mix of: cut or postpone scope (deliver the essential first), move the date, add money, change the approach (simplify, buy instead of build, outsource), stop the project. Adding people late tends to slow work down in the short term, as Brooks observed for software teams: check whether the newcomers can be useful quickly.
4. **Compare them** on time, cost, quality and risk (`decision-making`), and recommend one.
5. **Decide with the decision owner**, then rebuild the schedule and the budget from the new baseline, with buffers.
6. **Announce it** to everyone concerned: what happened, what changes, the new dates, and what is done so that it does not happen again (`stakeholder-map`, `status-update`).

## Output

```markdown
### Recovery plan: <project> (<date>)
Gap: … days late, … over budget | Main causes: 1. … 2. …
| Option | New date | Extra cost | What we give up | Risk |
|---|---|---|---|---|
Recommendation: … | Decided by: … on <date>
New milestones: … | Message to the people involved: …
```

## Quality bar

- The remaining work is re-estimated, not assumed.
- Causes are named and acted on, not only symptoms.
- At least three options, including cutting scope and stopping.
- The new plan has buffers and is announced to everyone concerned.
- Written in the user's language, with the terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Recovery plan | Plan de redressement | Plan de recuperación |
| Baseline | Référence, plan de base | Línea base |
| Root cause | Cause racine | Causa raíz |
| Scope cut | Réduction du périmètre | Reducción del alcance |
| Replanning | Replanification | Replanificación |
| Go or no-go | Décision de poursuivre ou non | Decisión de continuar o no |

## Sources

- Brooks, F. P. (1975). *The Mythical Man-Month: Essays on Software Engineering*. Addison-Wesley.
- Flyvbjerg, B., & Gardner, D. (2023). *How Big Things Get Done*. Currency.
