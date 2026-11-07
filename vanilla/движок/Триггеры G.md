---
type: reference
description: "Справочник движка Victoria 3 1.13: Триггеры G — 15, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры G

Из дампа `triggers.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **game_date** — Compare to current game date · `current_game_date = 1837.1.1 Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-game-date
- **gdp_ownership_ratio** — Compares the ratio of GDP the specified country owns in the scoped country Reads gamestate for all scopes. · `gdp_ownership_ratio = { target = scope:owner_country value > 0.1 } Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-gdp-ownership-ratio
- **gdp_per_capita_ranking** — Compares a Country's GDP per Capita Ranking (position) Reads gamestate for all scopes. · `gdp_per_capita_ranking > 42 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-gdp-per-capita-ranking
- **gdp_ranking** — Compares a Country's GDP Ranking (position) Reads gamestate for all scopes. · `gdp_ranking > 42 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-gdp-ranking
- **global_country_ranking** — Compares a Country's Power Ranking (position) Reads gamestate for all scopes. · `global_country_ranking > 42 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-global-country-ranking
- **global_population** — Compares the global population · `global_population > 2000000000 Traits: <, <=, =, !=, >, >=` · supported scopes: none ^t-global-population
- **global_variable_list_size** — Checks the size of a variable list Where X is the name of the variable Where Y is a script value or number · `variable_list_size = { name = X target >= Y }` · supported scopes: none ^t-global-variable-list-size
- **global_variable_map_size** — Checks the size of a variable map Where X is the name of the variable map Where Y is a script value or number · `variable_map_size = { name = X value >= Y }` · supported scopes: none ^t-global-variable-map-size
- **gold_reserves** — Does the country have the required gold reserves Reads gamestate for all scopes. · `gold_reserves > 500 Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-gold-reserves
- **gold_reserves_limit** — Compares the country's gold reserves limit gold_reserves > gold_reserves_limit Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-gold-reserves-limit
- **goods_production_rank** — Compare to a country's production leaderboard rank of a good "goods_production_rank(g:luxury_clothes)" < 10 Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-goods-production-rank
- **government_legitimacy** — Compare Legitimacy Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-government-legitimacy
- **government_transfer_of_power** — Checks country's government's transfer of power Reads gamestate for all scopes. · `government_transfer_of_power = key Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-government-transfer-of-power
- **government_wage_level** — Compares the government wage level of scoped country Reads gamestate for all scopes. · `government_wage_level = <level> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-government-wage-level
- **government_wage_level_value** — Compares the government wage level value of scoped country Reads gamestate for all scopes. · `government_wage_level_value = <level> Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-government-wage-level-value
