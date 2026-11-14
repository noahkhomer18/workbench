---
name: scope-change
description: >
  Handle a new request in the middle of a project without letting the scope
  creep: write the request down, measure its impact on time, cost, quality and
  risk, give the decision to the right person, say yes, no or later with the
  trade-off made visible, and update the plan and the change log. Use when a
  client, a boss, a partner or a family member asks for "just one more thing",
  or when a project keeps growing. Triggers: "scope creep", "change request", "can
  we also add", "new requirement", "dérive du périmètre", "demande de
  modification", "on peut aussi ajouter", "avenant", "solicitud de cambio",
  "ampliación del alcance", "podemos añadir también".
---

# Scope change

Projects rarely blow up in one day; they grow one small request at a time. This skill gives every request a visible price in time and money, so that the person who decides can say yes knowingly.

## When to use

- When a new request arrives after the scope was agreed (`project-charter`).
- When a client or a partner keeps adding "small" things.
- Not when the whole project is off track: use `project-recovery`.

## Inputs

1. The request, and who made it.
2. The current scope, schedule and budget.
3. Any contract or agreement that frames changes (for example a quote that lists what is included).

## Method

1. **Write the request down** in one or two sentences, with the reason behind it and its urgency.
2. **Measure its impact**: extra tasks, days, cost, effect on quality and on the risk register, and what else gets delayed.
3. **Propose options**: add it with its cost and delay, swap it for something of similar size that is removed, do it later in a second phase, or decline it with the reason.
4. **Send it to the decision owner** named in the charter, not to whoever happens to be in the room.
5. **Record the decision** in a change log: request, impact, decision, date, who decided.
6. **Update the plan**: scope, schedule, budget and, for outside suppliers, a written amendment to the quote or contract before the work starts.

## Output

```markdown
### Change request <n>: <title> (requested by <who>, <date>)
Why: … | Urgency: …
Impact: +… days | +… cost | quality: … | risks: …
Options: add / swap for … / later / decline
Decision: … by <owner> on <date>

### Change log
| # | Request | Impact | Decision | Date | Decided by |
|---|---|---|---|---|---|
```

## Quality bar

- No request is accepted without its impact on time and cost.
- The decision owner decides, and the decision is logged.
- Work for an outside supplier changes only after a written amendment.
- Written in the user's language, with the terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Scope creep | Dérive du périmètre | Ampliación descontrolada del alcance |
| Change request | Demande de modification | Solicitud de cambio |
| Change log | Registre des modifications | Registro de cambios |
| Amendment | Avenant | Adenda, modificación del contrato |
| Trade-off | Arbitrage | Compromiso |
| Change control | Gestion des changements | Control de cambios |

## Sources

- Project Management Institute. (2021). *A Guide to the Project Management Body of Knowledge (PMBOK Guide)* (7th ed.). Project Management Institute.
