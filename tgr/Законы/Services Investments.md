---
type: concept
description: "Закон «Services Investments» — TGR 1.15, `economic_incentives_services`"
project: vic3
audience: agent
source: tgr
aliases: ["Services Investments", "economic_incentives_services"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_services
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_public.txt]
---
# Services Investments

Закон · `economic_incentives_services` · `common/laws/TGR_POLITICS_economic_incentives_public.txt:31`

## Поля

- **group**: [[tgr/Группы законов/Public Investments|Public Investments]]
- **icon**: `gfx/interface/icons/law_icons/colonial_resettlement.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-incorporation-speed-mult|state_incorporation_speed_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `0.05`
- **institution**: `institution_incentive_public`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-bureaucracy-tax-mult|building_group_bg_bureaucracy_tax_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-bureaucracy-throughput-add|building_group_bg_bureaucracy_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 58–65

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_public: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_economic_incentives_public: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_economic_incentives_public: neutral): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]]
- **Идеологии** (lawgroup_economic_incentives_public: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Этнонационализм (ideology_ethno_nationalist_movement)|Этнонационализм (ideology_ethno_nationalist_movement)]]
