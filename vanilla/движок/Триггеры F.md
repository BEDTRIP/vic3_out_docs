---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры F — 8, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры F

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **fixed_expenses** — Does the country have this amount of weekly fixed expenses Reads gamestate for all scopes. · `fixed_expenses > 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-fixed-expenses
- **fixed_income** — Does the country have this amount of weekly fixed income Reads gamestate for all scopes. · `fixed_income > 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-fixed-income
- **food_security** — Checks if a pop has a certain amount of food security Reads gamestate for all scopes. · `food_security = value Traits: <, <=, =, !=, >, >=` · supported scopes: pop ^t-food-security
- **formation_army_unit_type_fraction** — Checks that a formation has a certain percentage of a specific army unit type } } Reads gamestate for all scopes. · `scope:example_formation = { country_military_unit_type_fraction = { target = unit_type:key value >= 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: military_formation ^t-formation-army-unit-type-fraction
- **formation_ship_type_fraction** — Checks that a formation has a certain fraction of a specific ship type } Reads gamestate for all scopes. · `formation_ship_type_fraction = { target = ship_type:key value >= 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: military_formation ^t-formation-ship-type-fraction
- **fraction_of_levels_owned_by_country** — Compares the fraction of total levels of a building a country or investors in that country owns value > 0.5 Reads gamestate for all scopes. · `fraction_of_levels_owned_by_country = { target = c:GBR Traits: <, <=, =, !=, >, >=` · supported scopes: building ^t-fraction-of-levels-owned-by-country
- **free_arable_land** — Check free arable land in state Reads gamestate for all scopes. · `free_arable_land > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-free-arable-land
- **free_principle_slots** — Compare a power bloc's free principle slot count } Reads gamestate for all scopes. · `power_bloc = { free_principle_slots >= 2 Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-free-principle-slots
