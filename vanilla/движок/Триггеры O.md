---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры O — 9, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры O

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **obstinance** — Compares state obstinance Reads gamestate for all scopes. · `obstinance > 0.5 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-obstinance
- **occupancy** — Evaluates a building's current occupancy Reads gamestate for all scopes. · `occupancy < 0.25 Traits: <, <=, =, !=, >, >=` · supported scopes: building ^t-occupancy
- **or** — at least one entry inside trigger must be true · supported scopes: none ^t-or
- **organization** — Compares the Organization of the Military Formation in scope Reads gamestate for all scopes. · `organization <= define:NMilitary|MILITARY_FORMATION_ORGANIZATION_MIN Traits: <, <=, =, !=, >, >=` · supported scopes: military_formation ^t-organization
- **organization_target** — Compares the target Organization of the Military Formation in scope Reads gamestate for all scopes. · `organization_target < define:NMilitary|MILITARY_FORMATION_ORGANIZATION_MAX Traits: <, <=, =, !=, >, >=` · supported scopes: military_formation ^t-organization-target
- **overlord_can_decrease_subject_autonomy** — Check if an overlord can decrease a subject autonomy Traits: yes/no Reads gamestate for all scopes. · `overlord_can_decrease_subject_autonomy = bool` · supported scopes: country ^t-overlord-can-decrease-subject-autonomy
- **owes_obligation_to** — Checks if country in scope owes a obligation to event target Traits: country scope Reads gamestate for all scopes. · `owes_obligation_to = country` · supported scopes: country · supported targets: country ^t-owes-obligation-to
- **owns_entire_state_region** — Check if country owns entire region Reads gamestate for all scopes. · `owns_entire_state_region = key` · supported scopes: country ^t-owns-entire-state-region
- **owns_treaty_port_in** — Does country own the treaty port in assigned state region Reads gamestate for all scopes. · `owns_treaty_port_in = key` · supported scopes: country ^t-owns-treaty-port-in
