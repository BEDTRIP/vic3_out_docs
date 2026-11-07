---
type: concept
description: "Закон «Oil Investments» — TGR 1.13, `economic_incentives_extracting_oil`"
project: vic3
source: tgr
aliases: ["Oil Investments", "economic_incentives_extracting_oil"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_extracting_oil
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_resources.txt]
---
# Oil Investments

Закон · `economic_incentives_extracting_oil` · `common/laws/TGR_POLITICS_economic_incentives_resources.txt:105`

## Поля

- **group**: [[tgr/Группы законов/Resources Investments|Resources Investments]]
- **icon**: `gfx/interface/icons/ai_strategy_icons/industrial_expansion.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: [[vanilla/Технологии/Качалки|Качалки]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_secondary`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-tax-mult|building_group_bg_oil_extraction_tax_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-capitalists-pol-str-mult|country_capitalists_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 132–139

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_secondary: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]]
- **Идеологии** (lawgroup_economic_incentives_secondary: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
- **Идеологии** (lawgroup_economic_incentives_secondary: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_economic_incentives_secondary: strongly_disapprove): [[tgr/Идеологии/Луддит|Луддит]]
