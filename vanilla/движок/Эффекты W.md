---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты W — 2, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты W

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **while** — Repeats enclosed effects while limit criteria are met or until set iteration count is reached Default max of 1000. · `while = { limit = { <triggers> } <effects> } while = { count = 3 <effects> }` · supported scopes: none ^e-while
- **withdraw** — Withdraws a country from a treaty } } · `scope:treaty = { withdraw = { country = <country> # must be valid and must be bound by the treaty apply_break_penalties = yes/no # optional, default no. If yes, break effects and on-actions apply whe…` · supported scopes: treaty ^e-withdraw
