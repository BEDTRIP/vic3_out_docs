---
type: concept
description: "Черта персонажа «Native Ruler» — Gates of Bosphorus 1.15, `gbbf_trait_native_ruler`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Native Ruler", "gbbf_trait_native_ruler"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_native_ruler
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_skill_traits.txt]
---
# Native Ruler

Черта персонажа · `gbbf_trait_native_ruler` · `common/character_traits/gbbf_skill_traits.txt:142`

## Поля

- **type**: `skill`
- **texture**: `gfx/interface/icons/character_trait_icons/imperious.dds`
- **value**: `0`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-command-limit-mult|character_command_limit_mult]] = `0.25`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pol-str-mult|interest_group_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pop-attraction-mult|interest_group_pop_attraction_mult]] = `0.05`
- **possible**: скрипт, строки 162–168
- **weight**: скрипт, строки 169–182
- **replace**: [[vanilla/Черты/Ребёнок|Ребёнок]]
