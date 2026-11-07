---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты J — 3, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты J

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **join_power_bloc** — Scoped country joins the power bloc of the target scoped country · `join_power_bloc = c:USA` · supported scopes: country · supported targets: country ^e-join-power-bloc
- **join_revolution** — Adds interest group to ongoing revolution · `join_revolution = yes/no` · supported scopes: interest_group ^e-join-revolution
- **join_war** — Makes target join a scoped war in a specific side. · `join_war = { target = scope:target_country side = root }` · supported scopes: war ^e-join-war
