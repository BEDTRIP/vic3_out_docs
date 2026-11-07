---
type: concept
description: "Закон «Manufacturing Investments» — TGR 1.13, `economic_incentives_industry_manufactoring`"
project: vic3
source: tgr
aliases: ["Manufacturing Investments", "economic_incentives_industry_manufactoring"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_industry_manufactoring
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_industry.txt]
---
# Manufacturing Investments

Закон · `economic_incentives_industry_manufactoring` · `common/laws/TGR_POLITICS_economic_incentives_industry.txt:31`

## Поля

- **group**: [[tgr/Группы законов/Industrial Investments|Industrial Investments]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/placate_population.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-goods-input-mult|building_goods_input_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_tertiary`
- **institution_modifier**:
  - `building_group_bg_consumer_goods_tax_mult` = `-0.05`
  - `building_group_bg_consumer_goods_throughput_add` = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-shopkeepers-pol-str-mult|country_shopkeepers_pol_str_mult]] = `0.20`
- **on_activate**: скрипт, строки 58–62
- **ai_enact_weight_modifier**: скрипт, строки 64–71

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_tertiary: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: neutral): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Джингоизм|Джингоизм]], [[tgr/Идеологии/Луддит|Луддит]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_economic_incentives_tertiary: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
