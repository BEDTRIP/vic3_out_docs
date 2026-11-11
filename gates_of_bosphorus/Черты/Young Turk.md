---
type: concept
description: "Черта персонажа «Young Turk» — Gates of Bosphorus 1.15, `gbbf_trait_young_turk`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Young Turk", "gbbf_trait_young_turk"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_young_turk
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_personality_traits.txt]
---
# Young Turk

Черта персонажа · `gbbf_trait_young_turk` · `common/character_traits/gbbf_personality_traits.txt:210`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/gbbf_young_turk.dds`
- **value**: `1`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-prominence-add|character_prominence_add]] = `10`
  - [[vanilla/движок/Модификаторы C#^m-character-loyalty-add|character_loyalty_add]] = `-5`
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `15`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы U#^m-unit-kill-rate-add|unit_kill_rate_add]] = `0.05`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pop-attraction-mult|interest_group_pop_attraction_mult]] = `0.05`
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-pop-attraction-mult|political_movement_pop_attraction_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-activism-growth-mult|political_movement_activism_growth_mult]] = `0.10`
- **possible**: скрипт, строки 232–239
- **weight**: скрипт, строки 240–266
