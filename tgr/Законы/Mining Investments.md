---
type: concept
description: "Закон «Mining Investments» — TGR 1.13, `economic_incentives_extracting_mining`"
project: vic3
source: tgr
aliases: ["Mining Investments", "economic_incentives_extracting_mining"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_extracting_mining
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_resources.txt]
---
# Mining Investments

Закон · `economic_incentives_extracting_mining` · `common/laws/TGR_POLITICS_economic_incentives_resources.txt:31`

## Поля

- **group**: [[tgr/Группы законов/Resources Investments|Resources Investments]]
- **icon**: `gfx/interface/icons/law_icons/extraction_economy.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-resource-discovery-chance-mult|country_resource_discovery_chance_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_secondary`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-tax-mult|building_group_bg_mining_tax_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-engineers-pol-str-mult|country_engineers_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 58–65

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_secondary: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]]
- **Идеологии** (lawgroup_economic_incentives_secondary: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Луддит|Луддит]]
- **Идеологии** (lawgroup_economic_incentives_secondary: neutral): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
