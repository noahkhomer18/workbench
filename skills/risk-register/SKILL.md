---
name: risk-register
description: >
  Find what could go wrong before it does: run a premortem ("it is six months
  later and the project failed: why?"), rate each risk by likelihood and impact,
  give it an owner, a prevention plan, a warning sign and a plan B, and keep the
  register alive during the project. Use when someone asks what could go wrong,
  before committing money or a date, or when a project starts to feel fragile.
  Triggers: "risks", "what could go wrong", "premortem", "risk register", "plan
  B", "risques", "qu'est-ce qui peut mal tourner", "registre des risques", "plan
  de secours", "riesgos", "qué puede salir mal", "registro de riesgos".
---

# Risk register

Teams that imagine their project has already failed find more of its real risks than teams that ask "any risks?". This skill uses that premortem, then turns the answers into a short register with owners and warning signs.

## When to use

- After `project-charter` and before committing money or a date.
- Before a big step: signing a contract, starting works, launching, migrating.
- When the project starts to feel fragile.

## Inputs

1. The charter, schedule and budget if they exist.
2. The people involved, ideally in the same room or the same thread.
3. What went wrong in similar past projects.

## Method

1. **Run a premortem** (Klein): "Imagine it is the deadline and the project failed badly. Write down every reason why." Each person writes alone first, then the list is shared; this brings out risks people hesitate to mention.
2. **Group and rewrite** each risk as cause, event and consequence: "Because the electrician is fully booked, the works could start late, delaying the move by a month."
3. **Rate likelihood and impact** on a simple 1 to 3 scale, with a sentence that justifies each rating.
4. **Plan the response** for the top risks: avoid, reduce, transfer (insurance, contract clause, guarantee) or accept with a plan B. Give each one an owner and a cost.
5. **Define a warning sign** for each top risk: the observable fact that says it is happening (no confirmation from the supplier 10 days before the date).
6. **Keep it alive**: review it at each milestone and in `status-update`; close risks that passed, add new ones.

## Output

```markdown
### Risk register: <project> (reviewed <date>)
| # | Risk (cause, event, consequence) | Likelihood (1-3) | Impact (1-3) | Response | Owner | Warning sign | Plan B |
|---|---|---|---|---|---|---|---|
```

## Quality bar

- Risks are specific to this project, written as cause, event and consequence.
- Each top risk has an owner, a response, a warning sign and a plan B.
- Ratings are justified, and the register has a review date.
- Insurance, guarantees and legal obligations are checked on official sources with the date when they are part of the response.
- Written in the user's language, with the terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Risk register | Registre des risques | Registro de riesgos |
| Premortem | Analyse pré-mortem | Análisis pre mortem |
| Likelihood, impact | Probabilité, impact | Probabilidad, impacto |
| Mitigation | Mesure de réduction | Medida de mitigación |
| Contingency plan, plan B | Plan de secours | Plan de contingencia |
| Warning sign | Signal d'alerte | Señal de alerta |

## Sources

- Klein, G. (2007). Performing a project premortem. *Harvard Business Review*, 85(9), 18–19.
- International Organization for Standardization. (2018). *ISO 31000:2018 Risk management: Guidelines*. ISO.
