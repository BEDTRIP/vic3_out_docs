---
type: concept
description: "Черта персонажа «Marabout» — Gates of Bosphorus 1.13, `gbbf_trait_marabout`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Marabout", "gbbf_trait_marabout"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_marabout
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_skill_traits.txt]
---
# Marabout

Черта персонажа · `gbbf_trait_marabout` · `common/character_traits/gbbf_skill_traits.txt:115`

## Поля

- **type**: `skill`
- **texture**: `gfx/interface/icons/character_trait_icons/gbbf_marabout.dds`
- **value**: `2`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pol-str-mult|interest_group_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.10`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.25`
- **interest_group_modifier**: пусто
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-pop-attraction-mult|political_movement_pop_attraction_mult]] = `0.05`
- **possible**: скрипт, строки 134–136
- **weight**:
  - `value` = `0`
