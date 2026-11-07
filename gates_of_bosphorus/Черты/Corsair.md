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
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-ship-detection-mult|ship_detection_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-visibility-mult|ship_visibility_mult]] = `-0.15`
  - [[vanilla/движок/Модификаторы S#^m-ship-ship-type-submarine-hull-damage-mult|ship_ship_type_submarine_hull_damage_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pop-attraction-mult|interest_group_pop_attraction_mult]] = `0.10`
- **affected_naval_mission_types**: `naval_mission_type_raid_supply`, `naval_mission_type_piracy`, `naval_mission_type_hunt_pirates`
- **possible**: скрипт, строки 24–26
- **weight**:
  - `value` = `0`
