---
type: concept
description: "Черта персонажа «Жестокость (cruel)» — ваниль 1.13, `cruel`"
project: vic3
source: vanilla
aliases: ["Жестокость (cruel)", "Cruel", "cruel"]
tags: [ваниль, черта]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: cruel
paths: [.vanillaVIC3/common/character_traits/personality_traits.txt]
---
# Жестокость (cruel)

Черта персонажа · `cruel` · `common/character_traits/personality_traits.txt:483`

## Поля

- **type**: `personality`
- **texture**: `gfx/interface/icons/character_trait_icons/cruel.dds`
- **character_modifier**:
  - `character_popularity_add` = `-50`
- **command_modifier**:
  - `unit_kill_rate_add` = `0.10`
- **country_modifier**:
  - `country_authority_mult` = `0.1`
  - `country_consumption_tax_cost_mult` = `-0.25`
  - `country_opposition_ig_approval_add` = `-1`
  - `state_standard_of_living_add` = `-1`
- **agitator_modifier**: пусто
- **interest_group_modifier**:
  - `interest_group_in_government_approval_add` = `1`
- **executive_modifier**:
  - `building_group_bg_heavy_industry_throughput_add` = `0.05`
  - `building_group_bg_heavy_industry_mortality_mult` = `0.10`
  - `building_group_bg_military_industry_throughput_add` = `0.05`
  - `building_group_bg_military_industry_mortality_mult` = `0.10`
  - `building_group_bg_plantations_throughput_add` = `0.05`
  - `building_group_bg_plantations_mortality_mult` = `0.10`
  - `building_group_bg_mining_throughput_add` = `0.05`
  - `building_group_bg_mining_mortality_mult` = `0.10`
  - `building_group_bg_agriculture_throughput_add` = `0.05`
  - `building_group_bg_agriculture_mortality_mult` = `0.10`
- **possible**: скрипт, строки 526–528
- **weight**: `1`
- **value**: `3`
