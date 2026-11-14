<div align="center">

# workbench

**Project skills for your AI agent, for any project, personal or professional.**

Project charter · Stakeholders · Decisions · Task breakdown · Schedule · Budget · Risks · RACI · Meetings · Status updates · Delegation · Quotes · Weekly review · Recovery · Retrospective

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-16-black.svg)](#the-skills)
[![Languages](https://img.shields.io/badge/languages-EN%20%7C%20FR%20%7C%20ES-green.svg)](#works-in-english-french-and-spanish)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**English** · [Français](README.fr.md) · [Español](README.es.md)

</div>

---

Most projects do not fail for lack of effort. The goal was vague, the schedule optimistic, the budget forgot half the costs, and nobody knew who decided. That is as true for a kitchen renovation as for a software migration.

**workbench** gives your agent the habits of an experienced project manager: a one-page charter before anything else, plans that account for our natural optimism, budgets built from real quotes, one owner per task and per decision, and short written updates. Every skill produces something you can use today: a charter, a task table for your spreadsheet, a Gantt chart, an agenda, minutes, a brief.

## Install

**Most coding agents** (Claude Code, Codex, Cursor, Windsurf, Cline and more):

```bash
npx skills add teodstr/workbench -g
```

**Claude Code**, as a plugin:

```
/plugin marketplace add teodstr/workbench
/plugin install workbench@workbench
```

**Manually:** copy the folders in [`skills/`](skills) into your agent's skills directory.

## Use it

Just ask. The right skill loads on its own.

```
We're renovating our kitchen in March with a €25k budget. Help me plan it.
Prépare l'ordre du jour de la réunion de copropriété sur le ravalement.
Compara estos tres presupuestos de mudanza y dime cuál elegir.
Our CRM migration is three weeks late. What are our options?
Organise ma semaine : j'ai trois projets au travail et un déménagement.
```

## The skills

| Skill | What it does |
|---|---|
| **Frame** | |
| [`project-charter`](skills/project-charter/SKILL.md) | A one-page charter: why, a goal you can check, scope, deadline, budget, who decides, first steps |
| [`stakeholder-map`](skills/stakeholder-map/SKILL.md) | Everyone the project affects, ranked by influence and interest, with a communication plan |
| [`decision-making`](skills/decision-making/SKILL.md) | A documented choice between options: criteria, decision matrix, bias check |
| **Plan** | |
| [`work-breakdown`](skills/work-breakdown/SKILL.md) | Deliverables cut into tasks, three-point estimates, dependencies, owners |
| [`project-schedule`](skills/project-schedule/SKILL.md) | A realistic schedule: critical path, buffers, milestones, Gantt chart |
| [`project-budget`](skills/project-budget/SKILL.md) | A budget built from quotes, with a reserve, a payment calendar and a tracker |
| [`risk-register`](skills/risk-register/SKILL.md) | A premortem, then risks with owners, warning signs and a plan B |
| [`responsibility-matrix`](skills/responsibility-matrix/SKILL.md) | Who does what (RACI), with one accountable person per task and decision |
| **Run** | |
| [`meeting-toolkit`](skills/meeting-toolkit/SKILL.md) | Agendas built on decisions, and minutes with actions, owners and dates |
| [`status-update`](skills/status-update/SKILL.md) | Short, honest updates that lead with the status and the decisions needed |
| [`delegation-brief`](skills/delegation-brief/SKILL.md) | A brief that lets someone else do the task well: intent, result, limits, check-ins |
| [`vendor-selection`](skills/vendor-selection/SKILL.md) | Quotes compared line by line, risks and buyer rules checked before signing |
| [`weekly-review`](skills/weekly-review/SKILL.md) | A 30-minute weekly review across all your projects, ending with a realistic week |
| **Adjust and close** | |
| [`project-recovery`](skills/project-recovery/SKILL.md) | A late or over-budget project: real gap, causes, options, a new credible plan |
| [`scope-change`](skills/scope-change/SKILL.md) | New requests with their price in time and money, decided by the right person |
| [`retrospective`](skills/retrospective/SKILL.md) | Lessons learned without blame, and a proper project closure |

## What every skill enforces

- **A goal you can check.** Everyone knows what "done" means and when.
- **Realistic plans.** Schedules and budgets correct for our natural optimism, with explicit buffers and reserves.
- **One owner per task and per decision.** Nothing falls between people.
- **Facts with a date.** Prices, rules and guarantees come from quotes and official pages, with the date, never from memory.
- **Something you can use today.** A charter, a table, a chart, an agenda or a brief.

## Works with boardroom and garage

workbench runs any project. [boardroom](https://github.com/teodstr/boardroom) analyzes a business (SWOT, Porter, market sizing…) and [garage](https://github.com/teodstr/garage) helps start a company (idea validation, MVP, funding…). Install the ones you need: they work side by side.

## Works in English, French and Spanish

Ask in any of the three languages and the agent answers with the words project teams actually use: *note de cadrage*, *rétroplanning*, *devis*, *acta de constitución*, *cronograma*, *presupuesto*… Adding a language to the terminology tables is one of the easiest ways to contribute.

## Not legal or financial advice

workbench helps you plan and decide. For contracts, taxes or legal obligations, check the official sources the skills point to and ask a professional when the stakes are high.

## Contributing

workbench is built so that anyone can contribute, even without ever writing code: a skill is a single Markdown file.

- **Add a skill** from the [roadmap](ROADMAP.md): event planning, house move, home renovation, kanban board…
- **Add your country** to `vendor-selection`: the official pages that protect buyers.
- **Add a language** to the terminology tables, or translate this README.
- **Report a weak output:** open an issue with your prompt and what the agent produced.

Start with [CONTRIBUTING.md](CONTRIBUTING.md). Every pull request is checked automatically.

## License

[MIT](LICENSE). Maintained by [teodstr](https://github.com/teodstr). Built with the help of Claude.
