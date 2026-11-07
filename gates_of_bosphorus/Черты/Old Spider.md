---
type: concept
description: "Черта персонажа «Old Spider» — Gates of Bosphorus 1.13, `gbbf_trait_old_spider`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Old Spider", "gbbf_trait_old_spider"]
tags: [gates_of_bosphorus, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_trait_old_spider
paths: [for addon/gatesofbosphorus/common/character_traits/gbbf_special_traits.txt]
---
# Old Spider

Черта персонажа · `gbbf_trait_old_spider` · `common/character_traits/gbbf_special_traits.txt:1`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/special_character_traits/special_character_el_excelentisimo.dds`
- **value**: `1`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `50`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `200`
  - [[vanilla/движок/Модификаторы C#^m-country-improve-relations-speed-mult|country_improve_relations_speed_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-infamy-generation-mult|country_infamy_generation_mult]] = `-0.10`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-recovery-mult|unit_morale_recovery_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы U#^m-unit-supply-consumption-mult|unit_supply_consumption_mult]] = `-0.10`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pop-attraction-mult|interest_group_pop_attraction_mult]] = `0.10`
- **possible**: скрипт, строки 22–24
- **weight**:
  - `value` = `0`
