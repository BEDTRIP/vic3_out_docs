---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры T — 29, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры T

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **taking_loans** — Check if the country is currently running a weekly deficit and taking loans to compensate Traits: yes/no Reads gamestate for all scopes. · supported scopes: country ^t-taking-loans
- **target_cohesion_number** — Compare the target Cohesion as a numeric value Reads gamestate for all scopes. · `target_cohesion_number > 50 Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-target-cohesion-number
- **target_cohesion_percentage** — Compare the target Cohesion as a percentage of the maximum of a Power Bloc in scope Reads gamestate for all scopes. · `target_cohesion_percentage > 0.5 Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-target-cohesion-percentage
- **target_is** — Checks who the target of a diplomatic play is Traits: country scope Reads gamestate for all scopes. · `target_is = country` · supported scopes: diplomatic_play · supported targets: country ^t-target-is
- **tax_capacity** — Checks the taxation capacity of the scoped state Reads gamestate for all scopes. · `tax_capacity > 50 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-tax-capacity
- **tax_capacity_usage** — Checks the taxation capacity usage of the scoped state Reads gamestate for all scopes. · `tax_capacity_usage > 50 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-tax-capacity-usage
- **tax_level** — Compares the overall tax level of scoped country Reads gamestate for all scopes. · `tax_level = <level> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tax-level
- **tax_level_value** — Compares the overall tax level integer value of scoped country Reads gamestate for all scopes. · `income_tax_level_value = <level> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tax-level-value
- **tax_waste** — Compare the tax waste of the country Reads gamestate for all scopes. · `tax_waste > 100 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tax-waste
- **tenure_in_current_power_bloc_days** — Compare the number of days the country in scope has been a member of their current Power Bloc Reads gamestate for all scopes. · `tenure_in_current_power_bloc_days > 720 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tenure-in-current-power-bloc-days
- **tenure_in_current_power_bloc_months** — Compare the number of (whole) months the country in scope has been a member of their current Power Bloc Reads gamestate for all scopes. · `tenure_in_current_power_bloc_months > 20 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tenure-in-current-power-bloc-months
- **tenure_in_current_power_bloc_weeks** — Compare the number of (whole) weeks the country in scope has been a member of their current Power Bloc Reads gamestate for all scopes. · `tenure_in_current_power_bloc_weeks > 12 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tenure-in-current-power-bloc-weeks
- **tenure_in_current_power_bloc_years** — Compare the number of (whole) years the country in scope has been a member of their current Power Bloc Reads gamestate for all scopes. · `tenure_in_current_power_bloc_years > 5 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-tenure-in-current-power-bloc-years
- **total_expenses** — Does the country have this amount of expenses, including from temporary sources Reads gamestate for all scopes. · `total_expenses > 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-total-expenses
- **total_income** — Does the country have this amount of income, including from temporary sources Reads gamestate for all scopes. · `total_income > 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-total-income
- **total_population** — Compares the total population of a given country Reads gamestate for all scopes. · `total_population > 100000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-total-population
- **total_population_including_subjects** — Compares the total population in the scope country and its subjects Reads gamestate for all scopes. · `total_population_including_subjects > 40000000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-total-population-including-subjects
- **total_population_including_subjects_share** — Compares the total population in the scope country and its subjects' share of the global population Reads gamestate for all scopes. · `total_population_including_subjects_share > 0.4 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-total-population-including-subjects-share
- **total_population_share** — Compares the total population of a given country's share of the global population Reads gamestate for all scopes. · `total_population_share > 0.02 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-total-population-share
- **total_size** — Compares the total size of the scoped pop Reads gamestate for all scopes. · `total_size >= 3000 Traits: <, <=, =, !=, >, >=` · supported scopes: pop ^t-total-size
- **total_urbanization** — Compares the total urbanization of a given state/ntotal_urbanization > 5 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-total-urbanization
- **total_used_principle_levels** — Compare a power bloc's total number of active principle levels Reads gamestate for all scopes. · `power_bloc = { total_used_principle_levels >= 10} Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-total-used-principle-levels
- **trait_value** — Compares the character's total trait value Reads gamestate for all scopes. · `trait_value < experience_level Traits: <, <=, =, !=, >, >=` · supported scopes: character ^t-trait-value
- **transfer_money_gross_income** — Does the country have this amount of gross income (income before expenses) from money transfer treaties ransfer_money_gross_income > 1000 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-transfer-money-gross-income
- **transfer_money_net_income** — Does the country have this amount of net income (income after expenses) from money transfer treaties ransfer_money_net_income > 1000 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-transfer-money-net-income
- **trigger_else** — `Evaluates the triggers if the display_triggers of preceding 'trigger_if' or 'trigger_else_if' is not mettrigger_if = { limit = { <display_triggers> } <triggers> } trigger_else = { <triggers> }` · supported scopes: none ^t-trigger-else
- **trigger_else_if** — `Evaluates the enclosed triggers if the display_triggers of the preceding 'trigger_if' or 'trigger_else_if' is not met and its own display_trigger of the limit is mettrigger_if = { limit = { <display_…` · supported scopes: none ^t-trigger-else-if
- **trigger_if** — Evaluates the triggers if the display_triggers of the limit are met · `trigger_if = { limit = { <display_triggers> } <triggers> }` · supported scopes: none ^t-trigger-if
- **turmoil** — Compares the turmoil in a given state, i.e. the fraction of Radicals Reads gamestate for all scopes. · `turmoil > 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-turmoil
