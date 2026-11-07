---
type: concept
description: "Черта персонажа «Elected Ruler» — Gates of Bosphorus 1.13, `gbbf_trait_elected_ruler`"
project: vic3
source: gates_of_bosphorus
aliases: ["Elected Ruler", "gbbf_trait_elected_ruler"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_elected_ruler
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_skill_traits.txt]
---
# Elected Ruler

Черта персонажа · `gbbf_trait_elected_ruler` · `common/character_traits/gbbf_skill_traits.txt:63`

## Поля

- **type**: `skill`
- **texture**: `gfx/interface/icons/character_trait_icons/social_banditry.dds`
- **value**: `1`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `25`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-base-add|country_legitimacy_base_add]] = `5`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.1`
- **possible**: скрипт, строки 78–80
- **weight**:
  - `value` = `0`
