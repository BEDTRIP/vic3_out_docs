---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты I — 3, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты I

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **if** — Executes enclosed effects if limit criteria are met · `if = { limit = { <triggers> } <effects> }` · supported scopes: none ^e-if
- **improve_stance** — `Improves the stance of an IG on the currently enacting law by the given number of steps: improve_stance = value` · supported scopes: interest_group ^e-improve-stance
- **increase_autonomy** — Change a country's subject type to a more autonomus one · `increase_autonomy = yes` · supported scopes: country ^e-increase-autonomy
