---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры E — 20, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры E

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **earnings** — Compare a building's current annual earnings per employee Reads gamestate for all scopes. · `earnings >= 10 Traits: <, <=, =, !=, >, >=` · supported scopes: building ^t-earnings
- **economic_dependence** — Compares the degree of dependence the country in scope has to the target country. Note: This is an expensive trigger Reads gamestate for all scopes. · `economic_dependence = { target = scope:other_country value > 2.2 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-economic-dependence
- **election_momentum** — Compare election momentum of the scoped party against a value Reads gamestate for all scopes. · `election_momentum = 0.75 Traits: <, <=, =, !=, >, >=` · supported scopes: party ^t-election-momentum
- **electoral_confidence** — Compares the electoral confidence of scope country Reads gamestate for all scopes. · `electoral_confidence > 0.1 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-electoral-confidence
- **empty_agitator_slots** — Checks number of empty agitator slots in a country Reads gamestate for all scopes. · `empty_agitator_slots >= 1 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-empty-agitator-slots
- **enacting_any_law** — Checks if you're enacting any law. Traits: yes/no Reads gamestate for all scopes. · `enacting_any_law = bool` · supported scopes: country ^t-enacting-any-law
- **enactment_chance** — Compares the current enactment success chance in scope country (including values from enactment modifier) Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enactment-chance
- **enactment_chance_for_law** — Compares the enactment success chance in scope country for given law (including values from enactment modifier) Reads gamestate for all scopes. · `enactment_chance_for_law = { target = scope:my_lawtype value > 0.2 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enactment-chance-for-law
- **enactment_chance_for_law_without_enactment_modifier** — Compares the enactment success chance in scope country for given law but excludes values from enactment modifier Reads gamestate for all scopes. · `enactment_chance_for_law_without_enactment_modifier = { target = scope:my_lawtype value > 0.2 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enactment-chance-for-law-without-enactment-modifier
- **enactment_chance_without_enactment_modifier** — Compares the current enactment success chance in scope country but excludes values from enactment modifier Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enactment-chance-without-enactment-modifier
- **enactment_phase** — Compares the current law enactment phase in scope country. Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enactment-phase
- **enactment_setback_count** — Compares the current enactment setback count in scope country. Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enactment-setback-count
- **enemy_contested_wargoals** — Determines the fraction of war goals that enemies in the war are currently contesting Reads gamestate for all scopes. · `enemy_contested_wargoals = { target = scope:war value > 0.4 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enemy-contested-wargoals
- **enemy_occupation** — Determines the (weighted) enemy occupation score of a country Reads gamestate for all scopes. · `enemy_occupation > 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-enemy-occupation
- **escalation** — Checks whether escalation has passed a certain threshold Reads gamestate for all scopes. · `escalation > -58 Traits: <, <=, =, !=, >, >=` · supported scopes: diplomatic_play ^t-escalation
- **exists** — Checks whether the specified scope target exists (check for not being the null object) · `exists = from.owner.var:cool_var.mother` · supported scopes: none ^t-exists
- **expanding_institution** — Checks if the institution is expanding Reads gamestate for all scopes. · `expanding_institution = <scope/key>` · supported scopes: country ^t-expanding-institution
- **experience_level** — Compares the character experience level Reads gamestate for all scopes. · `experience_level > 1 Traits: <, <=, =, !=, >, >=` · supported scopes: character ^t-experience-level
- **export_advantage** — Compare to state goods export advantage Reads gamestate for all scopes. · `export_advantage >= 100 Traits: <, <=, =, !=, >, >=` · supported scopes: state_goods ^t-export-advantage
- **export_tariff_level** — Checks if state goods has a particular export tariff level set Reads gamestate for all scopes. · `export_tariff_level = max_tariffs` · supported scopes: state_goods ^t-export-tariff-level
