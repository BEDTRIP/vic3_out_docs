---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры Y — 3, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры Y

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **year** — Compares the current year of the game · `year > 1850 Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-year
- **years_of_service** — Compares the commander's years of service Reads gamestate for all scopes. · `years_of_service > 1 Traits: <, <=, =, !=, >, >=` · supported scopes: character ^t-years-of-service
- **years_to_incorporate** — Checks how many years it would take for target country to incorporate scope state value > 5 Reads gamestate for all scopes. · `years_to_incorporate = { target = c:FRA Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-years-to-incorporate
