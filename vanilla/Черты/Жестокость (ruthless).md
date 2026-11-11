---
type: concept
description: "Черта персонажа «Жестокость (ruthless)» — ваниль 1.15, `ruthless`"
project: vic3
audience: agent
source: vanilla
aliases: ["Жестокость (ruthless)", "Ruthless", "ruthless"]
tags: [ваниль, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ruthless
paths: [.vanillaVIC3/common/character_traits/personality_traits.txt]
---
# Жестокость (ruthless)

Черта персонажа · `ruthless` · `common/character_traits/personality_traits.txt:977`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/ruthless.dds`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `-15`
  - [[vanilla/движок/Модификаторы C#^m-character-prominence-add|character_prominence_add]] = `5`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-piracy-income-add|country_piracy_income_add]] = `0.05`
- **agitator_modifier**:
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-add|political_movement_radicalism_add]] = `0.10`
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-pol-str-mult|interest_group_pol_str_mult]] = `0.15`
- **executive_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-throughput-add|building_group_bg_heavy_industry_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-mortality-mult|building_group_bg_heavy_industry_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-military-industry-throughput-add|building_group_bg_military_industry_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-military-industry-mortality-mult|building_group_bg_military_industry_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-mortality-mult|building_group_bg_mining_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-mortality-mult|building_group_bg_plantations_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-mortality-mult|building_group_bg_agriculture_mortality_mult]] = `0.10`
- **possible**: скрипт, строки 1016–1021
- **weight**: скрипт, строки 1023–1031
- **value**: `3`
