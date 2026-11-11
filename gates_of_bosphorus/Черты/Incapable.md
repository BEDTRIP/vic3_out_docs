---
type: concept
description: "Черта персонажа «Incapable» — Gates of Bosphorus 1.15, `gbbf_trait_incapable`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Incapable", "gbbf_trait_incapable"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_incapable
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_condition_traits.txt]
---
# Incapable

Черта персонажа · `gbbf_trait_incapable` · `common/character_traits/gbbf_condition_traits.txt:1`

## Поля

- **type**: `condition`
- **texture**: `gfx/interface/icons/character_trait_icons/psychological_affliction.dds`
- **value**: `0`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-health-add|character_health_add]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `-50`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-command-limit-mult|character_command_limit_mult]] = `-0.50`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `-200`
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `-0.05`
- **possible**: скрипт, строки 18–20
- **weight**:
  - `value` = `0`
