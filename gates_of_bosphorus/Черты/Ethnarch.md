---
type: concept
description: "Черта персонажа «Ethnarch» — Gates of Bosphorus 1.15, `gbbf_trait_ethnarch`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Ethnarch", "gbbf_trait_ethnarch"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_ethnarch
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_personality_traits.txt]
---
# Ethnarch

Черта персонажа · `gbbf_trait_ethnarch` · `common/character_traits/gbbf_personality_traits.txt:100`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/erudite.dds`
- **value**: `1`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.2`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.1`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pol-str-mult|interest_group_pol_str_mult]] = `0.25`
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-pop-attraction-mult|political_movement_pop_attraction_mult]] = `0.10`
- **possible**: скрипт, строки 122–124
- **weight**:
  - `value` = `0`
