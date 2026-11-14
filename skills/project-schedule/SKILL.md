---
name: project-schedule
description: >
  Build a realistic project schedule: order the tasks by dependencies, find the
  critical path, add buffers against our natural optimism, set milestones, check
  the plan against similar past projects, and draw it as a table or a Mermaid
  Gantt chart. Use when someone asks for a timeline, a planning, a Gantt chart, a
  deadline check ("can we finish by June?") or a calendar for any project.
  Triggers: "schedule", "timeline", "Gantt", "deadline", "how long will it take",
  "planning", "rétroplanning", "calendrier du projet", "diagramme de Gantt",
  "délais", "cronograma", "calendario del proyecto", "diagrama de Gantt", "plazos".
---

# Project schedule

People underestimate how long their own projects will take, even when they know that their past projects ran late: Buehler, Griffin and Ross called it the planning fallacy. This skill builds a schedule that corrects for it.

## When to use

- After `work-breakdown`, once tasks, owners and estimates exist.
- To check whether a deadline is realistic, or to work backward from a fixed date.
- Not for the cost side: use `project-budget`.

## Inputs

1. The task list with estimates and dependencies (`work-breakdown`).
2. Fixed dates: deadline, holidays, availability of each person, delivery dates.
3. Past projects of the same kind, if any, and how long they really took.

## Method

1. **Order the tasks** by their dependencies and the availability of each person; nobody works on two full-time tasks at once.
2. **Find the critical path**: the chain of dependent tasks that sets the end date. Any delay on it delays the whole project.
3. **Check against reality** (Flyvbjerg's reference class forecasting): how long did similar projects take, and how far did they overrun? Adjust the plan toward that outside view, not toward the best case.
4. **Add buffers** where the risk is: one shared buffer at the end of the critical path and before each fixed external date, rather than padding every task.
5. **Set milestones**: a few dated checkpoints that anyone can verify (permit received, walls painted, beta tested).
6. **Work backward** when the date is fixed: start from the deadline, place milestones, and show what must be cut or added if the plan does not fit.
7. **Draw it**: a table and a Mermaid Gantt chart that renders in many editors.

## Output

````markdown
### Schedule: <project> (version <n>, <date>)
| Task | Owner | Start | End | Depends on | Critical path |
|---|---|---|---|---|---|

Milestones: … | Buffer: … days before <date> | Confidence: …

```mermaid
gantt
  dateFormat YYYY-MM-DD
  section <deliverable>
  <task> :t1, <start>, <duration>d
```
````

## Quality bar

- The critical path is named, and the end date depends on it.
- The plan is compared with similar past projects, and buffers are explicit.
- Dates respect real availability (holidays, part-time, other work).
- When a fixed deadline does not fit, the schedule says so and shows the options.
- Written in the user's language, with the terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Schedule | Planning, calendrier | Cronograma, calendario |
| Critical path | Chemin critique | Ruta crítica |
| Milestone | Jalon | Hito |
| Buffer | Marge, tampon | Margen, colchón |
| Backward planning | Rétroplanning | Planificación inversa |
| Planning fallacy | Erreur de planification | Falacia de la planificación |

## Sources

- Buehler, R., Griffin, D., & Ross, M. (1994). Exploring the "planning fallacy": Why people underestimate their task completion times. *Journal of Personality and Social Psychology*, 67(3), 366–381.
- Flyvbjerg, B. (2006). From Nobel Prize to project management: Getting risks right. *Project Management Journal*, 37(3), 5–15.
- Mermaid Gantt syntax: https://mermaid.js.org/syntax/gantt.html
