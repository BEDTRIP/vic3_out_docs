---
type: concept
description: "Черта персонажа «Corsair» — Gates of Bosphorus 1.13, `gbbf_trait_corsair`"
project: vic3
source: gates_of_bosphorus
aliases: ["Corsair", "gbbf_trait_corsair"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_corsair
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_skill_traits.txt]
---
# Corsair

Черта персонажа · `gbbf_trait_corsair` · `common/character_traits/gbbf_skill_traits.txt:1`

## Поля

- **type**: `skill`
- **texture**: `gfx/interface/icons/character_trait_icons/gbbf_corsair.dds`
- **value**: `1`
- **character_modifier**:
  - `character_popularity_add` = `25`
- **command_modifier**:
  - `ship_detection_mult` = `0.1`
  - `ship_visibility_mult` = `-0.15`
  - `ship_ship_type_submarine_hull_damage_mult` = `0.1`
  - `character_popularity_add` = `25`
- **interest_group_modifier**:
  - `interest_group_pop_attraction_mult` = `0.10`
- **affected_naval_mission_types**: `naval_mission_type_raid_supply`, `naval_mission_type_piracy`, `naval_mission_type_hunt_pirates`
- **possible**: скрипт, строки 24–26
- **weight**:
  - `value` = `0`
