---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты M — 4, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты M

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **make_independent** — Makes a country independent. · `make_independent = bool` · supported scopes: country ^e-make-independent
- **mobilize_army** — Mobilizes scope army · `mobilize_army = yes` · supported scopes: military_formation ^e-mobilize-army
- **move_partial_pop** — Moves the scoped pop to the specified state (they become unemployed) NOTE: VERY IMPORTANT! This effect _may_ change the pop type of the moved pop. This will happen under the following conditions: 1. if the current pop type cannot be unemployed, the new pop type will be the default one 2.if the current pop type is a slave type and the target state does not allow slavery, the new pop type will be t… · `move_partial_pop = { state = s:STATE_TUSCANY.region_state:TUS } move_partial_pop = { state = s:STATE_TUSCANY.region_state:TUS population = 1000 } move_partial_pop = { state = s:STATE_TUSCANY.region_s…` · supported scopes: pop ^e-move-partial-pop
- **move_pop** — Moves the scoped pop in its entirety to the specified state (they become unemployed) NOTE: VERY IMPORTANT! This effect _may_ change the pop type of the moved pop. This will happen under the following conditions: 1. if the current pop type cannot be unemployed, the new pop type will be the default one 2.if the current pop type is a slave type and the target state does not allow slavery, the new po… · `move_pop = s:STATE_TUSCANY.region_state:TUS` · supported scopes: pop · supported targets: state ^e-move-pop
