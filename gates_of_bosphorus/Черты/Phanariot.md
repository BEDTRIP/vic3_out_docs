---
type: concept
description: "Черта персонажа «Phanariot» — Gates of Bosphorus 1.13, `gbbf_trait_phanariot`"
project: vic3
source: gates_of_bosphorus
aliases: ["Phanariot", "gbbf_trait_phanariot"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_phanariot
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_personality_traits.txt]
---
# Phanariot

Черта персонажа · `gbbf_trait_phanariot` · `common/character_traits/gbbf_personality_traits.txt:176`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/gbbf_fez.dds`
- **value**: `0`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `15`
  - [[vanilla/движок/Модификаторы C#^m-character-coup-strength-mult|character_coup_strength_mult]] = `0.10`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-influence-mult|country_influence_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-base-add|country_legitimacy_base_add]] = `5`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-command-limit-add|character_command_limit_add]] = `10`
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-loss-mult|unit_morale_loss_mult]] = `-0.05`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pop-attraction-mult|interest_group_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-in-opposition-approval-add|interest_group_in_opposition_approval_add]] = `-3`
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-pop-attraction-mult|political_movement_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-add|political_movement_radicalism_add]] = `0.05`
- **possible**: скрипт, строки 202–204
- **weight**:
  - `value` = `0`
