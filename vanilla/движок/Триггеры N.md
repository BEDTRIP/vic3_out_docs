---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры N — 35, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры N

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **nand** — a negated AND trigger · supported scopes: none ^t-nand
- **nationalization_cost** — Compares the total cost of nationalizing all buildings in scope country owned by the government or pops of target country Reads gamestate for all scopes. · `nationalization_cost = { target = scope:other_country value > 100000 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-nationalization-cost
- **naval_power_projection** — Compare to a country's total navy power projection Reads gamestate for all scopes. · `scope:example_country = { naval_power_projection < root.naval_power_projection Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-naval-power-projection
- **neighbors_any_power_bloc** — Checks if the scoped country neighbors any power bloc. Note: the scoped country is not considered to be neighboring the power bloc it belongs to (if any) Traits: yes/no Reads gamestate for all scopes. · `neighbors_any_power_bloc = yes/no` · supported scopes: country ^t-neighbors-any-power-bloc
- **neighbors_member_of_same_power_bloc** — Checks if the scoped country neighbors any other country belonging to the same power bloc Traits: yes/no Reads gamestate for all scopes. · `neighbors_member_of_same_power_bloc = yes/no` · supported scopes: country ^t-neighbors-member-of-same-power-bloc
- **neighbors_power_bloc** — Checks if the scoped country neighbors the target power bloc. Note: the scoped country is not considered to be neighboring the power bloc it belongs to (if any) Traits: power_bloc scope Reads gamestate for all scopes. · `neighbors_power_bloc = c:PRU.power_bloc` · supported scopes: country · supported targets: power_bloc ^t-neighbors-power-bloc
- **net_fixed_income** — Does the country have this amount of income after expenses (counting only fixed income & expenses) Reads gamestate for all scopes. · `net_fixed_income > 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-net-fixed-income
- **net_total_income** — Does the country have this amount of income after expenses (counting all income & expenses) Reads gamestate for all scopes. · `net_total_income > 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-net-total-income
- **night_value** — Night value · `Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-night-value
- **nor** — a negated OR trigger · supported scopes: none ^t-nor
- **not** — negates content of trigger · supported scopes: none ^t-not
- **num_casualties** — Checks the number of total casualties in the scoped war Reads gamestate for all scopes. · `num_casualties >= 5000 Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-num-casualties
- **num_companies** — How many companies the scoped country has Reads gamestate for all scopes. · `num_companies > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-num-companies
- **num_contraventions** — Check if the scoped article has the given number of contravention from the given country value > 0 } } Reads gamestate for all scopes. · `scope:treaty_article = { num_contraventions = { target = c:FRA Traits: <, <=, =, !=, >, >=` · supported scopes: treaty_article ^t-num-contraventions
- **num_country_casualties** — Checks the number of casualties for the target country in the scoped war Reads gamestate for all scopes. · `num_country_casualties = { target = country value < 5000 } Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-num-country-casualties
- **num_country_dead** — Checks the number of dead for the target country in the scoped war Reads gamestate for all scopes. · `num_country_dead = { target = country value < 5000 } Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-num-country-dead
- **num_country_wounded** — Checks the number of wounded for the target country in the scoped war Reads gamestate for all scopes. · `num_country_wounded = { target = country value < 5000 } Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-num-country-wounded
- **num_cultural_communities** — Check cultural communities in state Reads gamestate for all scopes. · `num_cultural_communities > 5 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-num-cultural-communities
- **num_dead** — Checks the number of total dead in the scoped war Reads gamestate for all scopes. · `num_dead >= 5000 Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-num-dead
- **num_diplomatic_pacts** — Compare to a country's number of diplomatic pacts of the specified type Reads gamestate for all scopes. · `num_diplomatic_pacts = { type = <key> value < 10 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-num-diplomatic-pacts
- **num_front_casualties** — Checks the number of casualties for the target country in the scoped front Reads gamestate for all scopes. · `num_front_casualties = { target = country value < 5000 } Traits: <, <=, =, !=, >, >=` · supported scopes: front ^t-num-front-casualties
- **num_front_dead** — Checks the number of dead for the target country in the scoped front Reads gamestate for all scopes. · `num_front_dead = { target = country value < 5000 } Traits: <, <=, =, !=, >, >=` · supported scopes: front ^t-num-front-dead
- **num_front_wounded** — Checks the number of wounded for the target country in the scoped front Reads gamestate for all scopes. · `num_front_wounded = { target = country value < 5000 } Traits: <, <=, =, !=, >, >=` · supported scopes: front ^t-num-front-wounded
- **num_investments_of_type** — Checks the number of buildings levels of a given type the scoped country has outside their own country. Reads gamestate for all scopes. · `num_investments_of_type = { type = building_oil_rig value > 5 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-num-investments-of-type
- **num_mobilized_units_in_theater** — Determines the number of mobilized units belonging to the scoped theater's owner or their allies, in fronts intersecting the scoped theater Reads gamestate for all scopes. · `num_mobilized_units_in_theater > 25 Traits: <, <=, =, !=, >, >=` · supported scopes: theater ^t-num-mobilized-units-in-theater
- **num_political_lobbies** — Compare to number of political lobbies in scoped country or interest group Reads gamestate for all scopes. · `num_political_lobbies > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: country, interest_group ^t-num-political-lobbies
- **num_potential_resources** — Checks the amount of the specified building type allowed in the state. Will return an error if used on building types that are not level capped Reads gamestate for all scopes. · `num_potential_resources(building_rubber_plantation) > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-num-potential-resources
- **num_power_bloc_members** — Compare the number of members in a power bloc against a value Reads gamestate for all scopes. · `num_power_bloc_members >= 2 Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-num-power-bloc-members
- **num_power_bloc_states** — Compare the number of states in a power bloc against a value Reads gamestate for all scopes. · `num_power_bloc_states >= 2 Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-num-power-bloc-states
- **num_provinces_in_theater** — Determines the number provinces in the scoped theater Reads gamestate for all scopes. · `num_provinces_in_theater > 10 Traits: <, <=, =, !=, >, >=` · supported scopes: theater ^t-num-provinces-in-theater
- **num_subjects** — Compares the number of subjects of scoped country Reads gamestate for all scopes. · `num_subjects = <value> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-num-subjects
- **num_taxed_goods** — Compares the number of consumption taxed goods of scoped country Reads gamestate for all scopes. · `num_taxed_goods = <value> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-num-taxed-goods
- **num_wounded** — Checks the number of total wounded in the scoped war Reads gamestate for all scopes. · `num_wounded >= 5000 Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-num-wounded
- **number_of_claims** — The number of claims on foreign states the country has Reads gamestate for all scopes. · `number_of_claims > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-number-of-claims
- **number_of_possible_decisions** — The number of possible Descision a Country can take umber_of_possible_decisions > 0 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-number-of-possible-decisions
