---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры R — 16, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры R

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **radical_fraction** — Compares radical fraction in pops in state or country, all parameters except value are optional Reads gamestate for all scopes. · `radical_fraction = { value = x pop_type = <key> strata = <key> culture = <key/scope> religion = <key/scope> } Traits: <, <=, =, !=, >, >=` · supported scopes: country, state ^t-radical-fraction
- **radical_population_fraction** — Compares the fraction of the population that are radicals in a given country Reads gamestate for all scopes. · `radical_population_fraction > 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-radical-population-fraction
- **real_month** — Compare to current real date month (Jan: 1, Dec: 12) · `real_month > 10 Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-real-month
- **region_score** — Compares the aggregated AI strategy region score for the specified strategic region in country scope Returns 0 in case the country is player controled Reads gamestate for all scopes. · `region_score = { strategic_region = sr:region_key value >= 300 } "region_score(sr:region_key)" >= 300 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-region-score
- **relative_authority** — Compares the unused fraction of authority for the scoped country Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-relative-authority
- **relative_bureaucracy** — Compares the unused fraction of bureaucracy for the scoped country Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-relative-bureaucracy
- **relative_export_advantage** — Compare to state goods relative export advantage Reads gamestate for all scopes. · `relative_export_advantage > 0.1 Traits: <, <=, =, !=, >, >=` · supported scopes: state_goods ^t-relative-export-advantage
- **relative_import_advantage** — Compare to state goodsrelative import advantage Reads gamestate for all scopes. · `relative_import_advantage > 0.1 Traits: <, <=, =, !=, >, >=` · supported scopes: state_goods ^t-relative-import-advantage
- **relative_influence** — Compares the unused fraction of influence for the scoped country Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-relative-influence
- **relative_infrastructure** — Compares the infrastructure to infrastructure usage of a state Reads gamestate for all scopes. · `relative_infrastructure > 1.1 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-relative-infrastructure
- **religion_percent_country** — Checks that a country's population has a certain percentage of a specific religion } } Reads gamestate for all scopes. · `scope:example_country = { religion_percent_country = { target = rel:catholic value <= 0.8 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-religion-percent-country
- **religion_percent_state** — Checks that a state's population has a certain percentage of a specific religion } } Reads gamestate for all scopes. · `scope:example_state = { religion_percent_state = { target = rel:catholic value <= 0.8 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-religion-percent-state
- **remaining_career_length** — Checks if the character's remaining career length meets a duration threshold. Role can be a specific database role, a role type, or omitted to use the role furthest from career end. Reads gamestate for all scopes. · `remaining_career_length = { role = general years = 5 }` · supported scopes: character ^t-remaining-career-length
- **remaining_undepleted** — Check remaining amount of resource, like gold mines in a state amount > 1 } Reads gamestate for all scopes. · `remaining_undepleted = { type = building_gold_mine Traits: <, <=, =, !=, >, >=` · supported scopes: state_region ^t-remaining-undepleted
- **role_priority** — Compares the priority of the character role Reads gamestate for all scopes. · `role_priority >= 10 Traits: <, <=, =, !=, >, >=` · supported scopes: character_role ^t-role-priority
- **ruler_can_have_command** — Checks if the country's government type allows its ruler to have command Traits: yes/no Reads gamestate for all scopes. · `ruler_can_have_command = yes/no` · supported scopes: country ^t-ruler-can-have-command
