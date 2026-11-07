---
type: concept
description: "Закон «Heavy Industry Investments» — TGR 1.13, `economic_incentives_industry_heavy`"
project: vic3
source: tgr
aliases: ["Heavy Industry Investments", "economic_incentives_industry_heavy"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_industry_heavy
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_industry.txt]
---
# Heavy Industry Investments

Закон · `economic_incentives_industry_heavy` · `common/laws/TGR_POLITICS_economic_incentives_industry.txt:117`

## Поля

- **group**: [[tgr/Группы законов/Industrial Investments|Industrial Investments]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/industrial_expansion.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - `country_military_goods_cost_mult` = `-0.10`
  - `country_bureaucracy_investment_cost_factor_mult` = `0.05`
- **institution**: `institution_incentive_tertiary`
- **institution_modifier**:
  - `building_group_bg_industry_heavy_tax_mult` = `-0.05`
  - `building_group_bg_industry_heavy_throughput_add` = `0.05`
  - `country_officers_pol_str_mult` = `0.20`
- **on_activate**: скрипт, строки 144–148
- **ai_enact_weight_modifier**: скрипт, строки 150–157

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_tertiary: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Джингоизм|Джингоизм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: strongly_disapprove): [[tgr/Идеологии/Луддит|Луддит]]
