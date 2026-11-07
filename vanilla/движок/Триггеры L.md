---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры L — 22, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры L

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **law_approved_by** — Checks whether the scoped law is approved by an interest group Reads gamestate for all scopes. · `law_approved_by = ig_rural_folk` · supported scopes: law ^t-law-approved-by
- **law_enactment_stance** — Compares the stance of the scoped character, movement or interest group has about enactment of the specified law compared to the current active law in the same group Reads gamestate for all scopes. · supported scopes: character, interest_group, political_movement ^t-law-enactment-stance
- **law_is_available** — Checks if a law is available for its country, considering its current situation. Like can_be_enacted, but ignores government support Traits: yes/no Reads gamestate for all scopes. · `law_is_available = yes` · supported scopes: law ^t-law-is-available
- **law_progressiveness_difference** — Compares the progressiveness of the scoped law type to the target law type, higher value means greater difference "law_progressiveness_difference( scope:target_law )" > 50 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: law_type ^t-law-progressiveness-difference
- **law_stance** — Compares the base stance of the scoped character, movement or interest group has about the specified law, ignoring the current active law in the same group Reads gamestate for all scopes. · supported scopes: character, interest_group, political_movement ^t-law-stance
- **leading_producer_of** — Checks if country is producing the most of a certain good Traits: goods scope Reads gamestate for all scopes. · `leading_producer_of = g:luxury_clothes` · supported scopes: country · supported targets: goods ^t-leading-producer-of
- **leads_customs_union** — Check if any other country is part of this country's customs union Traits: yes/no Reads gamestate for all scopes. · `leads_customs_union = bool` · supported scopes: country ^t-leads-customs-union
- **levels_owned_by_country** — Compares how many levels a country or investors in that country own in a building Reads gamestate for all scopes. · `levels_owned_by_country = { target = c:GBR value >= 1 Traits: <, <=, =, !=, >, >=` · supported scopes: building ^t-levels-owned-by-country
- **leverage_advantage** — Checks that the leverage advantage between power bloc and target country meets condition } Reads gamestate for all scopes. · `power_bloc = { leverage = { target = c:BEL value > 0 } Traits: <, <=, =, !=, >, >=` · supported scopes: power_bloc ^t-leverage-advantage
- **liberty_desire** — Compare trigger for the Liberty Desire value in a scoped country. Reads gamestate for all scopes. · `liberty_desire > 50 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-liberty-desire
- **liberty_desire_weekly_progress** — Compare trigger for the weekly Liberty Desire progress value in a scoped country. Reads gamestate for all scopes. · `liberty_desire_weekly_progress > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-liberty-desire-weekly-progress
- **liberty_desire_weekly_progress_from_support_independence** — Compare trigger for the weekly Liberty Desire progress value from the scoped country having their independence supported. Reads gamestate for all scopes. · `liberty_desire_weekly_progress_from_support_independence > 0 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-liberty-desire-weekly-progress-from-support-independence
- **lifetime_piracy_income** — Compares the lifetime piracy income of a character Reads gamestate for all scopes. · `lifetime_piracy_income >= 1000000 Traits: <, <=, =, !=, >, >=` · supported scopes: character ^t-lifetime-piracy-income
- **list_size** — Checks the size of a list Where X is the name of the list Where Y is a script value · `list_size = { name = X value >= Y } Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-list-size
- **literacy_rate** — Checks if a pop, state or country has a certain amount of literacy Reads gamestate for all scopes. · `literacy = value Traits: <, <=, =, !=, >, >=` · supported scopes: country, pop, state ^t-literacy-rate
- **lobby_clout** — Compare to total clout of scoped lobby's interest groups Reads gamestate for all scopes. · `lobby_clout >= 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: political_lobby ^t-lobby-clout
- **lobby_formation_reason** — Check scope diplomatic catalyst or political lobby scope for lobby formation reason Reads gamestate for all scopes. · `lobby_formation_reason = diplomacy` · supported scopes: diplomatic_catalyst, political_lobby ^t-lobby-formation-reason
- **local_variable_list_size** — Checks the size of a variable list Where X is the name of the variable Where Y is a script value or number · `variable_list_size = { name = X target >= Y }` · supported scopes: none ^t-local-variable-list-size
- **local_variable_map_size** — Checks the size of a variable map Where X is the name of the variable map Where Y is a script value or number · `variable_map_size = { name = X value >= Y }` · supported scopes: none ^t-local-variable-map-size
- **loyalist_fraction** — Compares loyalist fraction in pops in state or country, all parameters except value are optional Reads gamestate for all scopes. · `loyalist_fraction = { value = x pop_type = <key> strata = <key> culture = <key/scope> religion = <key/scope> } Traits: <, <=, =, !=, >, >=` · supported scopes: country, state ^t-loyalist-fraction
- **loyalists** — Compares the loyalty in a given state, i.e. the fraction of Loyalists Reads gamestate for all scopes. · `loyalists > 0.2 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-loyalists
- **loyalty** — Compares the character loyalty Reads gamestate for all scopes. · `loyalty > 1 Traits: <, <=, =, !=, >, >=` · supported scopes: character ^t-loyalty
