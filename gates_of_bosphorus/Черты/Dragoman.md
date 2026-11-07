---
type: concept
description: "Черта персонажа «Dragoman» — Gates of Bosphorus 1.13, `gbbf_trait_dragoman`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Dragoman", "gbbf_trait_dragoman"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_dragoman
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_skill_traits.txt]
---
# Dragoman

Черта персонажа · `gbbf_trait_dragoman` · `common/character_traits/gbbf_skill_traits.txt:32`

## Поля

- **type**: `skill`
- **texture**: `gfx/interface/icons/character_trait_icons/gbbf_dragoman.dds`
- **value**: `2`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
  - [[vanilla/движок/Модификаторы C#^m-character-prominence-add|character_prominence_add]] = `5`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.10`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.05`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pop-attraction-mult|interest_group_pop_attraction_mult]] = `0.1`
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-pop-attraction-mult|political_movement_pop_attraction_mult]] = `0.25`
- **possible**: скрипт, строки 55–57
- **weight**:
  - `value` = `0`
