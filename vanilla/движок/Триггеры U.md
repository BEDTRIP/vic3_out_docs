---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры U — 2, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры U

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **unit_formation_has_commander** — Checks if ther formation of the scoped combat unit has the provided character as one of its commanders Traits: character scope Reads gamestate for all scopes. · `unit_formation_has_commander = <character>` · supported scopes: new_combat_unit · supported targets: character ^t-unit-formation-has-commander
- **used_principle_slots** — Compare a power bloc's used principle slot count } Reads gamestate for all scopes. · `power_bloc = { used_principle_slots >= 2 Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-used-principle-slots
