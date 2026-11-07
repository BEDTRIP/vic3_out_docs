---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры W — 18, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры W

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **war_exhaustion_from_acceptance_of_dead** — Determines the war exhaustion a country gets from their degree of cultural acceptance of manpower killed in the war, regardless of what side they were on Reads gamestate for all scopes. · `war_exhaustion_from_acceptance_of_dead = { target = root value >= 0.4 Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-war-exhaustion-from-acceptance-of-dead
- **war_has_active_peace_deal** — True if the war has a proposed peace deal Traits: yes/no Reads gamestate for all scopes. · `war_has_active_peace_deal = bool` · supported scopes: war ^t-war-has-active-peace-deal
- **war_participant_has_war_goal_of_type_against** — Checks if scope country holds a war goal of a specific type targeting a specific country in any war Reads gamestate for all scopes. · `war_participant_has_war_goal_of_type_against = { type = <war goal type key>,target = <country scope> }` · supported scopes: country ^t-war-participant-has-war-goal-of-type-against
- **war_side_has_war_goal_of_type_against** — Checks if any country on the same side as scope country in any war holds a war goal of a specific type targeting a specific country Reads gamestate for all scopes. · `war_side_has_war_goal_of_type_against = { type =<war goal type key>, target = <country scope> }` · supported scopes: country ^t-war-side-has-war-goal-of-type-against
- **was_coerced_with_naval_threat** — Check if the scoped treaty was accepted through threatening naval hostilities Traits: yes/no Reads gamestate for all scopes. · `was_coerced_with_naval_threat = bool` · supported scopes: treaty ^t-was-coerced-with-naval-threat
- **was_exiled** — Checks whether the scoped character was exiled Traits: yes/no Reads gamestate for all scopes. · `was_exiled = yes/no` · supported scopes: character ^t-was-exiled
- **was_formed_from** — Check if a formed country previously had a specific definition Reads gamestate for all scopes. · `was_formed_from = <tag>` · supported scopes: country ^t-was-formed-from
- **wealth** — Checks if a pop has a certain amount of wealth Reads gamestate for all scopes. · `wealth = value Traits: <, <=, =, !=, >, >=` · supported scopes: pop ^t-wealth
- **wealth_share** — Checks the wealth political strength share of a pop type, religion or culture in a country or state. Exactly one of pop_type, religion or culture must be specified. value <compare operator> <value> } Reads gamestate for all scopes. · `wealth_share = { pop_type/religion/culture = <key/scope> Traits: <, <=, =, !=, >, >=` · supported scopes: country, state ^t-wealth-share
- **weekly_profit** — Checks whether the profits the building has made this week are above or below a given value Reads gamestate for all scopes. · `weekly_profit >= 20.0 Traits: <, <=, =, !=, >, >=` · supported scopes: building ^t-weekly-profit
- **weighted_calc_true_if** — Returns true if the sum of weights of fulfilled sub-triggers amount to the specified sum · `weighted_calc_true_if = { amount = 10 5 = { <trigger> } 15 = { <trigger> } 7 = { <trigger> } }` · supported scopes: none ^t-weighted-calc-true-if
- **workforce** — Compares the workforce size of the scoped pop Reads gamestate for all scopes. · `workforce >= 1000 Traits: <, <=, =, !=, >, >=` · supported scopes: pop ^t-workforce
- **world_market_access** — Checks the world market access of the scoped state Worldmarket_access > 0.8 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-world-market-access
- **world_market_delta** — Checks if goods has the specified number of exports minus imports in the world market Reads gamestate for all scopes. · `world_market_delta < X Where X = fixed point Traits: <, <=, =, !=, >, >=` · supported scopes: goods ^t-world-market-delta
- **world_market_exports** — Checks if goods has the specified number of exports in the world market Reads gamestate for all scopes. · `world_market_exports < X Where X = fixed point Traits: <, <=, =, !=, >, >=` · supported scopes: goods ^t-world-market-exports
- **world_market_imports** — Checks if goods has the specified number of imports in the world market Reads gamestate for all scopes. · `world_market_imports < X Where X = fixed point Traits: <, <=, =, !=, >, >=` · supported scopes: goods ^t-world-market-imports
- **would_accept_diplomatic_action** — Checks if a country would accept a diplomatic action proposed by another country if set, modify_acceptance will be added to their acceptance score, to allow for checking if they would accept with an obligation, etc Reads gamestate for all scopes. · `would_accept_diplomatic_action = { actor = <country scope> type = <action type key> first_state = <state scope, optional> second_state = <state scope, optional>, modify_acceptance = <script value, op…` · supported scopes: country ^t-would-accept-diplomatic-action
- **would_sponsor_amendment** — Check if scoped IG would sponsor an amendment of a given type Traits: amendment_type scope Reads gamestate for all scopes. · `would_sponsor_amendment = <amendment type scope>` · supported scopes: interest_group · supported targets: amendment_type ^t-would-sponsor-amendment
