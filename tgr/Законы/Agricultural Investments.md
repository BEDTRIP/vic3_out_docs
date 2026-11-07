---
type: concept
description: "Закон «Agricultural Investments» — TGR 1.13, `economic_incentives_agricolture`"
project: vic3
source: tgr
aliases: ["Agricultural Investments", "economic_incentives_agricolture"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: economic_incentives_agricolture
paths: [TheGreatRevision/common/laws/TGR_POLITICS_economic_incentives_agricolture.txt]
---
# Agricultural Investments

Закон · `economic_incentives_agricolture` · `common/laws/TGR_POLITICS_economic_incentives_agricolture.txt:31`

## Поля

- **group**: [[tgr/Группы законов/Agricultural investments|Agricultural investments]]
- **icon**: `gfx/interface/icons/law_icons/traditionalism.dds`
- **progressiveness**: `50`
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **modifier**:
  - `state_food_security_add` = `0.10`
  - `country_bureaucracy_investment_cost_factor_mult` = `0.05`
- **institution**: `institution_incentive_primary`
- **institution_modifier**:
  - `building_group_bg_agriculture_tax_mult` = `-0.05`
  - `building_group_bg_ranching_tax_mult` = `-0.05`
  - `building_group_bg_agriculture_throughput_add` = `0.05`
  - `building_group_bg_ranching_throughput_add` = `0.05`
  - `country_farmers_pol_str_mult` = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 60–67

## Ссылаются

- **Идеологии** (lawgroup_economic_incentives_primary: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_economic_incentives_primary: neutral): [[tgr/Идеологии/Government Policies (ideology_government_petty_bourgeoisie)|Government Policies (ideology_government_petty_bourgeoisie)]]
- **Идеологии** (lawgroup_economic_incentives_primary: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer)|Земельный реформатор (ideology_land_reformer)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer_movement)|Земельный реформатор (ideology_land_reformer_movement)]]
