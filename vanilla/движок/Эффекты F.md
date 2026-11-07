---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты F — 6, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты F

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **finish_harvest_condition** — Finish a harvest condition of type in the scoped state region · `finish_harvest_condition = <key>` · supported scopes: state_region ^e-finish-harvest-condition
- **finish_negotiation** — `Finishes the negotiation that has started for an interest group: finish_negotiation = yes/no` · supported scopes: interest_group ^e-finish-negotiation
- **force_resource_depletion** — Forces a resource depletion in state · `force_resource_depletion = bg_gold_mining` · supported scopes: state ^e-force-resource-depletion
- **force_resource_discovery** — Forces a resource discovery in state · `force_resource_discovery = bg_gold_mining` · supported scopes: state ^e-force-resource-discovery
- **free_character_from_void** — Frees a character from the void, if set to no character is deleted instead · `free_character_from_void = yes` · supported scopes: character ^e-free-character-from-void
- **fully_mobilize_army** — Fully mobilizes scope army · `fully_mobilize_army = yes` · supported scopes: military_formation ^e-fully-mobilize-army
