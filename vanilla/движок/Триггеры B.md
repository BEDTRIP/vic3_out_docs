---
type: reference
description: "Справочник движка Victoria 3 1.15.2: Триггеры B — 6, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Триггеры B

Из дампа `triggers.log` (2026-11-20; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **binds** — Checks if the scoped treaty or treaty_options binds the given country }} } Traits: country scope Reads gamestate for all scopes. · `scope:some_treaty = { if = { limit = { binds = c:FRA binds = c:BEL` · supported scopes: treaty_options, treaty · supported targets: country ^t-binds
- **blockade_level** — Compare to state's blockade level Reads gamestate for all scopes. · `blockade_level > 0.1 Traits: <, <=, =, !=, >, >=` · supported scopes: state ^t-blockade-level
- **blockaded_gdp_share** — Compares the share of the target country's GDP that sits in blockaded states, from the scoped war Reads gamestate for all scopes. · `blockaded_gdp_share = { target = root value >= 0.2 } Traits: <, <=, =, !=, >, >=` · supported scopes: war ^t-blockaded-gdp-share
- **building_has_goods_shortage** — Check if building has a shortage of any of its inputs Traits: yes/no Reads gamestate for all scopes. · `building_has_goods_shortage = yes/no` · supported scopes: building ^t-building-has-goods-shortage
- **bureaucracy** — Compares the available bureaucracy of the scoped country Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-bureaucracy
- **bureaucracy_usage** — Compares the consumed bureaucracy of the scoped country Reads gamestate for all scopes. · `Traits: <, <=, =, !=, >, >=` · supported scopes: country ^t-bureaucracy-usage
