---
type: reference
description: "Справочник движка Victoria 3 1.15.2: Эффекты L — 5, из дампа script_docs"
project: vic3
audience: agent
source: vanilla
tags: [ваниль, движок]
generated: "v3 graph engine"
---
# Эффекты L

Из дампа `effects.log` (2026-11-20; копия — `дамп/`). Генерат `v3 graph engine`: руками не править; дамп снят с набором модов — записи модов в нём тоже есть.

- **leave_plays_supporting** — Makes the scoped country leave every diplomatic play and war where it supports the target country, unless the scoped country is a primary participant · `leave_plays_supporting = scope:overlord` · supported scopes: country · supported targets: country ^e-leave-plays-supporting
- **leave_power_bloc** — Scoped country leaves its power bloc The country must be a core member, subjects follow their overlord instead If the country is the leader, leadership passes to the next eligible member, or the bloc is dissolved if there is none · `leave_power_bloc = yes` · supported scopes: country ^e-leave-power-bloc
- **liberate_slaves** — Frees all slaves in the country/state · `liberate_slaves = yes` · supported scopes: country, state ^e-liberate-slaves
- **liberate_slaves_in_incorporated_states** — Frees all slaves in the country's incorporated states · `liberate_slaves_in_incorporated_states = yes` · supported scopes: country ^e-liberate-slaves-in-incorporated-states
- **liberate_slaves_in_unincorporated_states** — Frees all slaves in the country's unincorporated states · `liberate_slaves_in_unincorporated_states = yes` · supported scopes: country ^e-liberate-slaves-in-unincorporated-states
