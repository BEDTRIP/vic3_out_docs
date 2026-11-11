---
type: concept
description: "Черта персонажа «Turkophagos» — Gates of Bosphorus 1.15, `gbbf_trait_turkophagos`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Turkophagos", "gbbf_trait_turkophagos"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_turkophagos
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_special_traits.txt]
---
# Turkophagos

Черта персонажа · `gbbf_trait_turkophagos` · `common/character_traits/gbbf_special_traits.txt:30`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/special_character_traits/special_character_napoleon_of_the_americas.dds`
- **value**: `1`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-command-limit-mult|character_command_limit_mult]] = `0.3`
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-character-battle-condition-surprise-maneuver-mult|character_battle_condition_surprise_maneuver_mult]] = `1.5`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `1`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pol-str-mult|interest_group_pol_str_mult]] = `0.05`
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-pop-attraction-mult|political_movement_pop_attraction_mult]] = `0.05`
- **possible**: скрипт, строки 51–53
- **weight**:
  - `value` = `3`
