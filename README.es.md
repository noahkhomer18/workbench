<div align="center">

# workbench

**Skills de gestión de proyectos para tu agente de IA, para cualquier proyecto, personal o profesional.**

Acta de constitución · Partes interesadas · Decisiones · Desglose de tareas · Cronograma · Presupuesto · Riesgos · RACI · Reuniones · Informes de estado · Delegación · Presupuestos de proveedores · Revisión semanal · Recuperación · Retrospectiva

[![Licencia: MIT](https://img.shields.io/badge/licencia-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-16-black.svg)](#las-skills)
[![Idiomas](https://img.shields.io/badge/idiomas-EN%20%7C%20FR%20%7C%20ES-green.svg)](#funciona-en-inglés-francés-y-español)
[![PR bienvenidas](https://img.shields.io/badge/PR-bienvenidas-brightgreen.svg)](CONTRIBUTING.md)

[English](README.md) · [Français](README.fr.md) · **Español**

</div>

---

La mayoría de los proyectos que fracasan no fracasan por falta de esfuerzo. El objetivo era vago, el cronograma optimista, el presupuesto olvidaba la mitad de los costes y nadie sabía quién decidía. Es igual de cierto para la reforma de una cocina que para la migración de un software.

**workbench** le da a tu agente los hábitos de un jefe de proyecto con experiencia: un acta de una página antes de nada, planes que tienen en cuenta nuestro optimismo natural, presupuestos hechos con presupuestos reales de proveedores, un responsable por tarea y por decisión, e informes de estado breves y por escrito. Cada skill produce algo que puedes usar hoy mismo: un acta, una tabla de tareas para tu hoja de cálculo, un diagrama de Gantt, un orden del día, un acta de reunión, un brief.

## Instalación

**La mayoría de los agentes de programación** (Claude Code, Codex, Cursor, Windsurf, Cline y otros):

```bash
npx skills add teodstr/workbench -g
```

**Claude Code**, como plugin:

```
/plugin marketplace add teodstr/workbench
/plugin install workbench@workbench
```

**A mano:** copia las carpetas de [`skills/`](skills) en la carpeta de skills de tu agente.

## Uso

Pregunta sin más. La skill adecuada se carga sola.

```
We're renovating our kitchen in March with a €25k budget. Help me plan it.
Prépare l'ordre du jour de la réunion de copropriété sur le ravalement.
Compara estos tres presupuestos de mudanza y dime cuál elegir.
Our CRM migration is three weeks late. What are our options?
Organise ma semaine : j'ai trois projets au travail et un déménagement.
```

## Las skills

| Skill | Qué hace |
|---|---|
| **Definir** | |
| [`project-charter`](skills/project-charter/SKILL.md) | Un acta de una página: por qué, un objetivo comprobable, alcance, fecha límite, presupuesto, quién decide, primeros pasos |
| [`stakeholder-map`](skills/stakeholder-map/SKILL.md) | Todas las personas afectadas, ordenadas por influencia e interés, con un plan de comunicación |
| [`decision-making`](skills/decision-making/SKILL.md) | Una elección documentada entre opciones: criterios, matriz de decisión, revisión de sesgos |
| **Planificar** | |
| [`work-breakdown`](skills/work-breakdown/SKILL.md) | Los entregables divididos en tareas, estimaciones de tres puntos, dependencias, responsables |
| [`project-schedule`](skills/project-schedule/SKILL.md) | Un cronograma realista: ruta crítica, márgenes, hitos, diagrama de Gantt |
| [`project-budget`](skills/project-budget/SKILL.md) | Un presupuesto hecho con presupuestos reales, con una reserva, un calendario de pagos y un seguimiento |
| [`risk-register`](skills/risk-register/SKILL.md) | Un análisis pre mortem y riesgos con responsables, señales de alerta y plan B |
| [`responsibility-matrix`](skills/responsibility-matrix/SKILL.md) | Quién hace qué (RACI), con un único responsable final por tarea y por decisión |
| **Gestionar** | |
| [`meeting-toolkit`](skills/meeting-toolkit/SKILL.md) | Órdenes del día basados en decisiones, y actas con acciones, responsables y fechas |
| [`status-update`](skills/status-update/SKILL.md) | Informes de estado breves y honestos, que empiezan por el estado y las decisiones necesarias |
| [`delegation-brief`](skills/delegation-brief/SKILL.md) | Un brief para que otra persona haga bien la tarea: intención, resultado, límites, puntos de control |
| [`vendor-selection`](skills/vendor-selection/SKILL.md) | Presupuestos comparados línea a línea, riesgos y normas que protegen al comprador revisados antes de firmar |
| [`weekly-review`](skills/weekly-review/SKILL.md) | Una revisión semanal de 30 minutos de todos tus proyectos, que acaba con una semana realista |
| **Ajustar y cerrar** | |
| [`project-recovery`](skills/project-recovery/SKILL.md) | Un proyecto retrasado o fuera de presupuesto: desfase real, causas, opciones, un nuevo plan creíble |
| [`scope-change`](skills/scope-change/SKILL.md) | Las nuevas peticiones con su precio en tiempo y dinero, decididas por la persona adecuada |
| [`retrospective`](skills/retrospective/SKILL.md) | Lecciones aprendidas sin buscar culpables, y un cierre de proyecto como es debido |

## Lo que exige cada skill

- **Un objetivo comprobable.** Todos saben qué significa «terminado» y para cuándo.
- **Planes realistas.** Cronogramas y presupuestos corrigen nuestro optimismo natural, con márgenes y reservas explícitos.
- **Un responsable por tarea y por decisión.** Nada se queda entre dos personas.
- **Hechos con fecha.** Precios, normas y garantías vienen de presupuestos y páginas oficiales, con la fecha, nunca de memoria.
- **Algo que puedes usar hoy.** Un acta, una tabla, un diagrama, un orden del día o un brief.

## Funciona con boardroom y garage

workbench hace avanzar cualquier proyecto. [boardroom](https://github.com/teodstr/boardroom) analiza una empresa (DAFO, Porter, tamaño de mercado…) y [garage](https://github.com/teodstr/garage) ayuda a crear una empresa (validar una idea, MVP, financiación…). Instala los que necesites: funcionan juntos.

## Funciona en inglés, francés y español

Pregunta en cualquiera de los tres idiomas y el agente responde con las palabras que de verdad usan los equipos de proyecto: *note de cadrage*, *rétroplanning*, *devis*, *acta de constitución*, *cronograma*, *presupuesto*… Añadir un idioma a las tablas de terminología es una de las formas más sencillas de contribuir.

## No es asesoramiento jurídico ni financiero

workbench te ayuda a planificar y a decidir. Para contratos, impuestos u obligaciones legales, comprueba las fuentes oficiales que indican las skills y consulta a un profesional cuando hay mucho en juego.

## Contribuir

workbench está pensado para que cualquiera pueda contribuir, aunque nunca haya escrito una línea de código: una skill es un solo archivo Markdown.

- **Añade una skill** de la [hoja de ruta](ROADMAP.md): organización de eventos, mudanza, reforma, tablero kanban…
- **Añade tu país** a `vendor-selection`: las páginas oficiales que protegen al comprador.
- **Añade un idioma** a las tablas de terminología, o traduce este README.
- **Informa de una respuesta floja:** abre un issue con tu prompt y lo que produjo el agente.

Empieza por [CONTRIBUTING.md](CONTRIBUTING.md) (en inglés). Cada pull request se comprueba automáticamente.

## Licencia

[MIT](LICENSE). Mantenido por [teodstr](https://github.com/teodstr). Hecho con la ayuda de Claude.
