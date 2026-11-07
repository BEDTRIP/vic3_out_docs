---
type: concept
description: "Закон «Public Sector Investments» — TGR 1.13, `economic_incentives_university`"
project: vic3
source: tgr
aliases: ["Public Sector Investments", "economic_incentives_university"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_university
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_public.txt]
---
# Public Sector Investments

Закон · `economic_incentives_university` · `common/laws/TGR_POLITICS_economic_incentives_public.txt:68`

## Поля

- **group**: [[tgr/Группы законов/Public Investments|Public Investments]]
- **icon**: `gfx/interface/icons/law_icons/public_schools.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - `country_ahead_of_time_research_penalty_mult` = `-0.10`
  - `country_bureaucracy_investment_cost_factor_mult` = `0.05`
- **institution**: `institution_incentive_public`
- **institution_modifier**:
  - `building_group_bg_technology_tax_mult` = `-0.05`
  - `building_university_throughput_add` = `0.05` → [[vanilla/Здания/Университеты|Университеты]]
  - `country_academics_pol_str_mult` = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 95–102

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_public: approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]], [[tgr/Идеологии/Джингоизм|Джингоизм]]
- **Идеологии** (lawgroup_economic_incentives_public: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_economic_incentives_public: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
