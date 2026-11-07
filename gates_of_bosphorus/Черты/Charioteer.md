---
type: concept
description: "Черта персонажа «Charioteer» — Gates of Bosphorus 1.13, `gbbf_trait_charioteer`"
project: vic3
source: gates_of_bosphorus
aliases: ["Charioteer", "gbbf_trait_charioteer"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_charioteer
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_personality_traits.txt]
---
# Charioteer

Черта персонажа · `gbbf_trait_charioteer` · `common/character_traits/gbbf_personality_traits.txt:71`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/erudite.dds`
- **value**: `1`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `50`
  - [[vanilla/движок/Модификаторы C#^m-character-prominence-add|character_prominence_add]] = `10`
  - [[vanilla/движок/Модификаторы C#^m-character-health-add|character_health_add]] = `-0.10`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-recovery-rate-add|unit_recovery_rate_add]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-character-coup-strength-mult|character_coup_strength_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-ship-vulnerability-mult|ship_vulnerability_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-ship-critical-hit-chance-mult|ship_critical_hit_chance_mult]] = `0.1`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-diplomatic-play-maneuvers-add|country_diplomatic_play_maneuvers_add]] = `20`
  - [[vanilla/движок/Модификаторы C#^m-country-infamy-generation-mult|country_infamy_generation_mult]] = `0.2`
- **possible**: скрипт, строки 92–94
- **weight**:
  - `value` = `0`
