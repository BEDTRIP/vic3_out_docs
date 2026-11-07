---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры D — 9, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры D

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **day_value** — Day value · `Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-day-value
- **daynight_value** — DayNight value · `Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-daynight-value
- **days_since_movement_defeated** — Compares the number of days since a movement with this identity was last defeated in civil war. Returns max value if never defeated. Reads gamestate for all scopes. · `days_since_movement_defeated >= <days> Traits: <, <=, =, !=, >, >=` · supported scopes: political_movement ^t-days-since-movement-defeated
- **days_since_movement_type_defeated** — Compares the number of days since a movement of a given identity was last defeated in civil war. Returns max value if never defeated. } Reads gamestate for all scopes. · `days_since_movement_type_defeated = { type = <key/scope> culture = <key/scope> (optional) religion = <key/scope> (optional) value >= <days> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-days-since-movement-type-defeated
- **debug_log** — Log whether the parent trigger succeeded or failed · supported scopes: none ^t-debug-log
- **debug_log_details** — Log whether the parent trigger succeeded or failed. Log which children succeeded or failed · supported scopes: none ^t-debug-log-details
- **dependents** — Compares the dependents size of the scoped pop Reads gamestate for all scopes. · `dependents >= 2000 Traits: <, <=, =, !=, >, >=` · supported scopes: pop ^t-dependents
- **devastation** — Compares the devastation of a given state Reads gamestate for all scopes. · `devastation > 5 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-devastation
- **discriminates_religion** — Checks if the scoped country discriminates the given religion (key) Reads gamestate for all scopes. · `discriminates_religion = <religion key/scope>` · supported scopes: country ^t-discriminates-religion
