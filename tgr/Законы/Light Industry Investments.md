---
type: concept
description: "Закон «Light Industry Investments» — TGR 1.15, `economic_incentives_industry_light`"
project: vic3
audience: agent
source: tgr
aliases: ["Light Industry Investments", "economic_incentives_industry_light"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_industry_light
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_industry.txt]
---
# Light Industry Investments

Закон · `economic_incentives_industry_light` · `common/laws/TGR_POLITICS_economic_incentives_industry.txt:74`

## Поля

- **group**: [[tgr/Группы законов/Industrial Investments|Industrial Investments]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/resource_expansion.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_tertiary`
- **institution_modifier**:
  - `building_group_bg_industry_light_tax_mult` = `-0.05`
  - `building_group_bg_industry_light_throughput_add` = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-capitalists-pol-str-mult|country_capitalists_pol_str_mult]] = `0.20`
- **on_activate**: скрипт, строки 101–105
- **ai_enact_weight_modifier**: скрипт, строки 107–114

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_tertiary: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Луддит|Луддит]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: neutral): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
