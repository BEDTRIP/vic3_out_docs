---
type: reference
description: "Справочник движка Victoria 3 1.13: Эффекты T — 7, из дампа script_docs"
project: vic3
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты T

Из дампа `effects.log` (2026-10-13; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **take_on_scaled_debt** — Transfers an amount of debt equal to the defined multiplier on target's max credit } · `take_on_scaled_debt = { who = <country> value = decimal value` · supported scopes: country ^e-take-on-scaled-debt
- **teleport_to_front** — Teleports the scope formation to the target front Can also take a base_camp parameter, will use given province to search for the nearest connected base camp · `teleport_to_front = p:xFAFAFA.front teleport_to_front = { front = p:xFAFAFA.front base_camp = p:xFAFAFA }` · supported scopes: military_formation ^e-teleport-to-front
- **transfer_character** — Transfers current scope character to target country · `transfer_character = country` · supported scopes: character · supported targets: country ^e-transfer-character
- **transfer_subject** — Transfers subject from another country to current scope country · `transfer_subject = scope` · supported scopes: country · supported targets: country ^e-transfer-subject
- **transfer_to_formation** — Transfers scope character to target formation · `transfer_to_formation = scope:formation` · supported scopes: character · supported targets: military_formation ^e-transfer-to-formation
- **trigger_event** — Triggers an event for the current scope Where X is an event ID and Y is an integer to delay the event by · `trigger_event = X trigger_event = { id = X days/weeks/months/years = Y }` · supported scopes: none ^e-trigger-event
- **try_form_government_with** — Tries to form a new govt with provided IGs, If not possible with legitimacy provided will try and add as many IGs into the govt as possible · `try_form_government_with = { value = 30 interest_group_type = ig_armed_forces interest_group_type = ig_devout interest_group_type = ig_landowners}` · supported scopes: country ^e-try-form-government-with
