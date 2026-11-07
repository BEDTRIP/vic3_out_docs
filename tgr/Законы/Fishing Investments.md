---
type: concept
description: "Закон «Fishing Investments» — TGR 1.13, `economic_incentives_fishing`"
project: vic3
source: tgr
aliases: ["Fishing Investments", "economic_incentives_fishing"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_fishing
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_agricolture.txt]
---
# Fishing Investments

Закон · `economic_incentives_fishing` · `common/laws/TGR_POLITICS_economic_incentives_agricolture.txt:107`

## Поля

- **group**: [[tgr/Группы законов/Agricultural investments|Agricultural investments]]
- **icon**: `gfx/interface/icons/law_icons/freeholders.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-food-security-add|state_food_security_add]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_primary`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-fishing-tax-mult|building_group_bg_fishing_tax_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-whaling-tax-mult|building_group_bg_whaling_tax_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-fishing-throughput-add|building_group_bg_fishing_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-whaling-throughput-add|building_group_bg_whaling_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-shopkeepers-pol-str-mult|country_shopkeepers_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 136–143

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_primary: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]]
- **Идеологии** (lawgroup_economic_incentives_primary: neutral): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer)|Земельный реформатор (ideology_land_reformer)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer_movement)|Земельный реформатор (ideology_land_reformer_movement)]]
