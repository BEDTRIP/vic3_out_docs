---
type: concept
description: "Черта персонажа «Жестокость (cruel)» — ваниль 1.15, `cruel`"
project: vic3
audience: agent
source: vanilla
aliases: ["Жестокость (cruel)", "Cruel", "cruel"]
tags: [ваниль, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: cruel
paths: [.vanillaVIC3/common/character_traits/personality_traits.txt]
---
# Жестокость (cruel)

Черта персонажа · `cruel` · `common/character_traits/personality_traits.txt:549`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/cruel.dds`
- **character_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-character-popularity-add|character_popularity_add]] = `-50`
- **command_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-kill-rate-add|unit_kill_rate_add]] = `0.10`
- **country_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-consumption-tax-cost-mult|country_consumption_tax_cost_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-opposition-ig-approval-add|country_opposition_ig_approval_add]] = `-1`
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `-1`
- **agitator_modifier**: пусто
- **interest_group_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-in-government-approval-add|interest_group_in_government_approval_add]] = `1`
- **executive_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-throughput-add|building_group_bg_heavy_industry_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-mortality-mult|building_group_bg_heavy_industry_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-military-industry-throughput-add|building_group_bg_military_industry_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-military-industry-mortality-mult|building_group_bg_military_industry_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-mortality-mult|building_group_bg_plantations_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-mortality-mult|building_group_bg_mining_mortality_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-mortality-mult|building_group_bg_agriculture_mortality_mult]] = `0.10`
- **possible**: скрипт, строки 592–594
- **weight**: `1`
- **value**: `3`
