---
name: work-breakdown
description: >
  Break a project into deliverables and tasks small enough to estimate and
  assign (a work breakdown structure), estimate each task with optimistic, likely
  and pessimistic durations, and spot dependencies, in a table that pastes into a
  spreadsheet or a to-do app. Use when a project feels too big to start, when
  someone asks for a task list or a plan, or before building a schedule. Triggers:
  "task list", "break down the project", "WBS", "to-do list for my project",
  "estimate", "liste des tâches", "découper le projet", "estimer les tâches",
  "lista de tareas", "desglosar el proyecto", "estimar tareas".
---

# Work breakdown

A project becomes manageable once it is cut into pieces that someone can finish in a few days. This skill builds that list, estimates it honestly and shows what depends on what.

## When to use

- After `project-charter`, before `project-schedule`.
- When a project feels too big or vague to start.
- Not for daily to-do management: use `weekly-review`.

## Inputs

1. The goal, scope and deliverables (from `project-charter`).
2. Who can work on it, and how much time each person has.
3. Anything already done.

## Method

1. **Start from the deliverables**, not from activities: what will exist at the end (a painted room, a signed contract, a migrated database).
2. **Break each deliverable down** until each task takes between a few hours and a few days, has a clear "done" and can be given to one person. Group tasks under their deliverable (a work breakdown structure).
3. **Check for forgotten work**: buying, waiting for deliveries, permits and paperwork, cleaning up, testing, telling people, training.
4. **Estimate with three numbers**: optimistic, most likely, pessimistic. The PERT average (optimistic + 4 × most likely + pessimistic) ÷ 6 gives a planning value, and the spread shows the uncertainty.
5. **Mark the dependencies**: what cannot start before something else is finished, and waiting times that cost no effort but take calendar time (drying, delivery, approval).
6. **Assign an owner** to each task (one name, not a team).
7. **Export the table** so that it pastes into a spreadsheet or a task app, then go to `project-schedule`.

## Output

```markdown
### Work breakdown: <project>
| ID | Deliverable | Task | Done when | Owner | Optimistic | Likely | Pessimistic | PERT | Depends on |
|---|---|---|---|---|---|---|---|---|---|
| 1.1 | … | … | … | … | 1 d | 2 d | 4 d | 2.2 d | – |
```

## Quality bar

- Every task has one owner, a clear "done" and a three-point estimate.
- Waiting times, paperwork, testing and communication are in the list.
- The PERT values are computed, not guessed, and estimates come from the people who will do the work when possible.
- Written in the user's language, with the terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Work breakdown structure (WBS) | Organigramme des tâches (WBS) | Estructura de desglose del trabajo (EDT) |
| Task | Tâche | Tarea |
| Dependency | Dépendance | Dependencia |
| Estimate | Estimation | Estimación |
| Three-point estimate | Estimation à trois points | Estimación de tres puntos |
| Owner | Responsable | Responsable |

## Sources

- Project Management Institute. (2021). *A Guide to the Project Management Body of Knowledge (PMBOK Guide)* (7th ed.). Project Management Institute.
- Malcolm, D. G., Roseboom, J. H., Clark, C. E., & Fazar, W. (1959). Application of a technique for research and development program evaluation. *Operations Research*, 7(5), 646–669.
