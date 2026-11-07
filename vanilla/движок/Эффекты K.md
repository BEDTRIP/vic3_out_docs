---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты K — 8, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты K

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **kill_character** — Kill a character } · `kill_character = bool (yes - kill [by default], no - don't do anything) kill_character = { hidden = bool (yes - without notification; no - show notification [by default]) value = bool (yes - kill [by…` · supported scopes: character ^e-kill-character
- **kill_crew** — Kills a given amount of a ship's crew · `kill_crew = 20` · supported scopes: ship ^e-kill-crew
- **kill_crew_percent** — Kills a given percentage of a ship's crew · `kill_crew_percent = 0.2` · supported scopes: ship ^e-kill-crew-percent
- **kill_population** — Kills a number of individuals in the population in the scoped country. } · `All parameters except percent are optional. Pop type and strata cannot be used at the same time.kill_population = { value = <integer value> culture = <scope/cu:key> religion = <scope/rel:key> interes…` · supported scopes: country ^e-kill-population
- **kill_population_in_state** — Kills a number of individuals in the population in the scoped state. } · `All parameters except percent are optional. Pop type and strata cannot be used at the same time.kill_population = { value = <integer value> culture = <scope/cu:key> religion = <scope/rel:key> interes…` · supported scopes: state ^e-kill-population-in-state
- **kill_population_percent** — Kills a percentage of the population in the scoped country. } · `All parameters except percent are optional. Pop type and strata cannot be used at the same time.kill_population_percent = { percent = <decimal value> culture = <scope/cu:key> religion = <scope/rel:ke…` · supported scopes: country ^e-kill-population-percent
- **kill_population_percent_in_state** — Kills a percentage of the population in the scoped state. } · `All parameters except percent are optional. Pop type and strata cannot be used at the same time.kill_population_percent = { percent = <decimal value> culture = <scope/cu:key> religion = <scope/rel:ke…` · supported scopes: state ^e-kill-population-percent-in-state
- **kill_ship** — Destroys the scoped ship · `kill_ship = bool # yes - destroy the ship [by default], no - don't do anything` · supported scopes: ship ^e-kill-ship
