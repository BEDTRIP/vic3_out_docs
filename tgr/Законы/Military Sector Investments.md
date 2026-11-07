---
type: concept
description: "Закон «Military Sector Investments» — TGR 1.13, `economic_incentives_military`"
project: vic3
audience: agent
source: tgr
aliases: ["Military Sector Investments", "economic_incentives_military"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_military
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_public.txt]
---
# Military Sector Investments

Закон · `economic_incentives_military` · `common/laws/TGR_POLITICS_economic_incentives_public.txt:105`

## Поля

- **group**: [[tgr/Группы законов/Public Investments|Public Investments]]
- **icon**: `gfx/interface/icons/law_icons/professional_army.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-morale-loss-mult|unit_morale_loss_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_public`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-military-tax-mult|building_group_bg_military_tax_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-military-throughput-add|building_group_bg_military_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 132–139

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_public: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
- **Идеологии** (lawgroup_economic_incentives_public: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_economic_incentives_public: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Джингоизм|Джингоизм]]
