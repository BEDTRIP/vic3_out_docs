---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты U — 4, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты U

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **unassign_from_formation** — Unassigns the scoped commander from their formation · `unassign_from_formation = yes` · supported scopes: character ^e-unassign-from-formation
- **unset_available_for_autonomous_investment** — Sets a building type as unavailable for autonomous investment in the current scoped State · `unset_available_for_autonomous_investment = building type scope` · supported scopes: state · supported targets: building_type ^e-unset-available-for-autonomous-investment
- **unset_only_legal_party** — Returns the country to a non single-party state state, where multiple parties can exist if they are allowed by other laws · `unset_only_legal_party = yes` · supported scopes: country ^e-unset-only-legal-party
- **update_party_support** — Updates party support in scoped country. · `update_party_support = yes` · supported scopes: country ^e-update-party-support
