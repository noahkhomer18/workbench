---
name: <skill-name, in kebab-case and identical to the folder name, for example move-planning>
description: >
  <What the skill does, in one or two sentences that start with a verb.>
  Use when <the situations and questions that should load this skill,
  in plain words>. Triggers: "<English keyword, as users type it>", "<another English
  keyword, …>", "<mot-clé en français, …>", "<autre mot-clé, …>", "<palabra clave en
  español, …>", "<otra palabra clave, …>".
---

<!--
How to use this template:
1. Copy this file to skills/<skill-name>/SKILL.md (the file must be named exactly SKILL.md).
2. Replace every <...> with your own words, then delete this comment.
3. Keep the section titles and their order: the automatic check looks for them.
4. Aim for 80 to 150 lines. Put long material in skills/<skill-name>/references/.
5. Run python3 scripts/validate_skills.py before you open a pull request.
-->

# <Skill title, in plain words>

<One or two sentences: the problem this skill solves for someone running a project, and what it does better than a generic answer.>

## When to use

- <A situation where someone needs this skill, in the words they would use.>
- <How it fits with the other skills, for example "after `project-charter`, to turn the goal into tasks".>
- Not for <a related need it does not cover, for example "choosing a contractor">: use `<other-skill, for example vendor-selection>` instead.

## Inputs

1. The project in a few sentences: goal, deadline, budget, who is involved.
2. <What the skill needs to know, for example the country, the team or the constraints.>
3. Anything the person already has. Ask for what is missing instead of guessing.

## Method

1. **<First step, for example "Write the goal in one sentence".>** <What to do, how to do it well, and the classic mistake to avoid.>
2. **<Second step, same format.>** <…>
3. **<Third step, same format.>** <…>
4. **Decide the next step.** <What the person does with the result, in two or three sentences.>

Every step relies on the person's material, a cited source or an official page checked during the conversation. When data is missing, state a clearly labeled assumption. Never invent figures, testimonials or results.

## Output

```markdown
### <Deliverable>: <project>
<A table, a script, a page or a short structure that the agent fills in.>

### Next step
<The decision, why, and the first concrete action.>
```

## Quality bar

- <A check specific to this skill, for example "every task has an owner and a date".>
- Facts that change (prices, laws, rules) come from an official page checked during the conversation, with the link and the date.
- The answer ends with a decision or a next step, not with a list.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| <term, as used in English> | <terme, tel qu'on l'emploie en français> | <término, tal como se usa en español> |

## Sources

- <Author, A. (Year). *Title of the book*. Publisher.>
- <Organization. (n.d.). *Title of the official page*. https://…>
