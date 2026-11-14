<div align="center">

# workbench

**Des skills de gestion de projet pour votre agent IA, pour tout projet, perso ou pro.**

Note de cadrage · Parties prenantes · Décisions · Découpage des tâches · Planning · Budget · Risques · RACI · Réunions · Points d'avancement · Délégation · Devis · Revue hebdomadaire · Redressement · Retour d'expérience

[![Licence : MIT](https://img.shields.io/badge/licence-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-16-black.svg)](#les-skills)
[![Langues](https://img.shields.io/badge/langues-EN%20%7C%20FR%20%7C%20ES-green.svg)](#fonctionne-en-anglais-en-français-et-en-espagnol)
[![PR bienvenues](https://img.shields.io/badge/PR-bienvenues-brightgreen.svg)](CONTRIBUTING.md)

[English](README.md) · **Français** · [Español](README.es.md)

</div>

---

La plupart des projets qui échouent ne manquent pas d'efforts. L'objectif était flou, le planning optimiste, le budget oubliait la moitié des coûts, et personne ne savait qui décidait. C'est aussi vrai pour la rénovation d'une cuisine que pour la migration d'un logiciel.

**workbench** donne à votre agent les réflexes d'un chef de projet expérimenté : une note de cadrage d'une page avant tout, des plannings qui tiennent compte de notre optimisme naturel, des budgets construits à partir de vrais devis, un responsable par tâche et par décision, et des points d'avancement courts et écrits. Chaque skill produit un livrable utilisable tout de suite : une note de cadrage, un tableau de tâches pour votre tableur, un diagramme de Gantt, un ordre du jour, un compte rendu, un brief.

## Installation

**La plupart des agents de code** (Claude Code, Codex, Cursor, Windsurf, Cline et d'autres) :

```bash
npx skills add teodstr/workbench -g
```

**Claude Code**, sous forme de plugin :

```
/plugin marketplace add teodstr/workbench
/plugin install workbench@workbench
```

**À la main :** copiez les dossiers de [`skills/`](skills) dans le dossier de skills de votre agent.

## Utilisation

Posez simplement votre question. Le bon skill se charge tout seul.

```
We're renovating our kitchen in March with a €25k budget. Help me plan it.
Prépare l'ordre du jour de la réunion de copropriété sur le ravalement.
Compara estos tres presupuestos de mudanza y dime cuál elegir.
Our CRM migration is three weeks late. What are our options?
Organise ma semaine : j'ai trois projets au travail et un déménagement.
```

## Les skills

| Skill | Ce qu'il fait |
|---|---|
| **Cadrer** | |
| [`project-charter`](skills/project-charter/SKILL.md) | Une note de cadrage d'une page : pourquoi, un objectif vérifiable, périmètre, échéance, budget, qui décide, premières étapes |
| [`stakeholder-map`](skills/stakeholder-map/SKILL.md) | Toutes les personnes concernées, classées par influence et par intérêt, avec un plan de communication |
| [`decision-making`](skills/decision-making/SKILL.md) | Un choix documenté entre plusieurs options : critères, matrice de décision, vérification des biais |
| **Planifier** | |
| [`work-breakdown`](skills/work-breakdown/SKILL.md) | Les livrables découpés en tâches, estimations à trois points, dépendances, responsables |
| [`project-schedule`](skills/project-schedule/SKILL.md) | Un planning réaliste : chemin critique, marges, jalons, diagramme de Gantt |
| [`project-budget`](skills/project-budget/SKILL.md) | Un budget construit à partir de devis, avec une provision, un échéancier et un suivi |
| [`risk-register`](skills/risk-register/SKILL.md) | Une analyse pré-mortem, puis des risques avec responsables, signaux d'alerte et plan B |
| [`responsibility-matrix`](skills/responsibility-matrix/SKILL.md) | Qui fait quoi (RACI), avec un seul responsable final par tâche et par décision |
| **Piloter** | |
| [`meeting-toolkit`](skills/meeting-toolkit/SKILL.md) | Des ordres du jour construits sur les décisions, et des comptes rendus avec actions, responsables et dates |
| [`status-update`](skills/status-update/SKILL.md) | Des points d'avancement courts et honnêtes, qui commencent par l'état du projet et les décisions attendues |
| [`delegation-brief`](skills/delegation-brief/SKILL.md) | Un brief qui permet à quelqu'un d'autre de bien faire la tâche : intention, résultat, limites, points d'étape |
| [`vendor-selection`](skills/vendor-selection/SKILL.md) | Des devis comparés ligne à ligne, risques et règles qui protègent l'acheteur vérifiés avant de signer |
| [`weekly-review`](skills/weekly-review/SKILL.md) | Une revue hebdomadaire de 30 minutes sur tous vos projets, qui se termine par une semaine réaliste |
| **Ajuster et clôturer** | |
| [`project-recovery`](skills/project-recovery/SKILL.md) | Un projet en retard ou hors budget : écart réel, causes, options, nouveau plan crédible |
| [`scope-change`](skills/scope-change/SKILL.md) | Les nouvelles demandes avec leur prix en temps et en argent, tranchées par la bonne personne |
| [`retrospective`](skills/retrospective/SKILL.md) | Un retour d'expérience sans chercher de coupable, et une vraie clôture de projet |

## Ce que chaque skill impose

- **Un objectif vérifiable.** Tout le monde sait ce que « terminé » veut dire, et pour quand.
- **Des plans réalistes.** Plannings et budgets corrigent notre optimisme naturel, avec des marges et des provisions explicites.
- **Un responsable par tâche et par décision.** Rien ne tombe entre deux personnes.
- **Des faits datés.** Prix, règles et garanties viennent de devis et de pages officielles, avec la date, jamais de mémoire.
- **Un livrable utilisable tout de suite.** Une note de cadrage, un tableau, un diagramme, un ordre du jour ou un brief.

## Fonctionne avec boardroom et garage

workbench fait avancer n'importe quel projet. [boardroom](https://github.com/teodstr/boardroom) analyse une entreprise (SWOT, Porter, taille de marché…) et [garage](https://github.com/teodstr/garage) aide à lancer une entreprise (validation d'idée, MVP, financements…). Installez ceux dont vous avez besoin : ils fonctionnent côte à côte.

## Fonctionne en anglais, en français et en espagnol

Posez votre question dans l'une des trois langues et l'agent répond avec les mots qu'emploient vraiment les équipes projet : *note de cadrage*, *rétroplanning*, *devis*, *acta de constitución*, *cronograma*, *presupuesto*… Ajouter une langue aux tableaux de terminologie est l'une des façons les plus simples de contribuer.

## Pas un conseil juridique ou financier

workbench aide à planifier et à décider. Pour les contrats, les impôts ou les obligations légales, vérifiez les sources officielles indiquées par les skills et demandez conseil à un professionnel quand les enjeux sont importants.

## Contribuer

workbench est pensé pour que tout le monde puisse contribuer, même sans avoir jamais écrit une ligne de code : un skill tient dans un seul fichier Markdown.

- **Ajoutez un skill** de la [feuille de route](ROADMAP.md) : organisation d'un événement, déménagement, rénovation, tableau kanban…
- **Ajoutez votre pays** au skill `vendor-selection` : les pages officielles qui protègent l'acheteur.
- **Ajoutez une langue** aux tableaux de terminologie, ou traduisez ce README.
- **Signalez une réponse faible :** ouvrez une issue avec votre prompt et ce que l'agent a produit.

Commencez par [CONTRIBUTING.md](CONTRIBUTING.md) (en anglais). Chaque pull request est vérifiée automatiquement.

## Licence

[MIT](LICENSE). Maintenu par [teodstr](https://github.com/teodstr). Réalisé avec l'aide de Claude.
