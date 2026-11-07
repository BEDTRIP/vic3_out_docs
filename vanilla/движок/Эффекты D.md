---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты D — 14, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты D

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **damage_ship_hull** — Damages a ship's hull by a given amount · `damage_ship_hull = 20` · supported scopes: ship ^e-damage-ship-hull
- **damage_ship_hull_percent** — Damages a ship's hull by a given percentage of its total health · `damage_ship_hull_percent = 0.2` · supported scopes: ship ^e-damage-ship-hull-percent
- **deactivate_building** — Deactivate a building in a state · `deactivate_building = { building = building_key }` · supported scopes: state ^e-deactivate-building
- **deactivate_law** — Deactivates a law for a country · supported scopes: country · supported targets: law_type ^e-deactivate-law
- **deactivate_parties** — Deactivates parties in scoped country. · `deactivate_parties = yes` · supported scopes: country ^e-deactivate-parties
- **debug_log** — `Log a string to the debug log when this effect executes, debug_log = message, the message can be a localization string with ROOT, SCOPE and PREV available` · supported scopes: none ^e-debug-log
- **debug_log_scopes** — Log the current scope to the debug log when this effect executes · `debug_log_scopes = yes # log full scope info debug_log_scopes = no # log only current scope` · supported scopes: none ^e-debug-log-scopes
- **decrease_autonomy** — Change a country's subject type to a less autonomus one · `decrease_autonomy = yes` · supported scopes: country ^e-decrease-autonomy
- **deploy_to_front** — Deploys the scope formation to the target front Can also take a base_camp parameter, will use given province to search for the nearest connected base camp · `deploy_to_front = p:xFAFAFA.front deploy_to_front = { front = p:xFAFAFA.front base_camp = p:xFAFAFA }` · supported scopes: military_formation ^e-deploy-to-front
- **destroy_container** — Destroys the script container in scope. · `destroy_container = yes` · supported scopes: container ^e-destroy-container
- **disable_temporary_hostilities** — Disable temporary hostilities of a given type between two countries } · `disable_temporary_hostilities = { country = country scope/tag type = naval/war/limited_war` · supported scopes: country ^e-disable-temporary-hostilities
- **disband_party** — Removes all interest groups from the party, causing it to disband · `disband_party = yes` · supported scopes: party ^e-disband-party
- **disband_political_lobby** — Disband scoped political lobby · `disband_political_lobby = yes` · supported scopes: political_lobby ^e-disband-political-lobby
- **disinherit_character** — Strips the scoped character of their heir status in whichever countries apply. · `scope:larry = { disinherit_character = yes }` · supported scopes: character ^e-disinherit-character
