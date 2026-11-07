---
type: concept
description: "Закон «Eco-Friendly Pollution Regulations» — TGR 1.13, `law_eco_environment_regulations`"
project: vic3
source: tgr
aliases: ["Eco-Friendly Pollution Regulations", "law_eco_environment_regulations"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_eco_environment_regulations
paths: [TheGreatRevision/common/laws/TGR_POLITICS_environment_regulations.txt]
---
# Eco-Friendly Pollution Regulations

Закон · `law_eco_environment_regulations` · `common/laws/TGR_POLITICS_environment_regulations.txt:106`

## Поля

- **group**: [[tgr/Группы законов/Pollution Regulations|Pollution Regulations]]
- **icon**: `gfx/interface/icons/law_icons/agrarianism.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[tgr/Технологии/Профилактика малярии|Профилактика малярии]]
- **institution**: `institution_environment`
- **institution_modifier**:
  - `state_pollution_reduction_health_mult` = `-0.05`
  - `country_mass_migration_attraction_mult` = `0.05`
  - `building_group_bg_mining_throughput_add` = `-0.03`
  - `building_group_bg_logging_throughput_add` = `-0.03`
  - `building_group_bg_oil_extraction_throughput_add` = `-0.03`
  - `building_group_bg_manufacturing_throughput_add` = `-0.03`
  - `interest_group_ig_rural_folk_pol_str_mult` = `0.10`
  - `interest_group_ig_rural_folk_pop_attraction_mult` = `0.20`
  - `country_farmers_pol_str_mult` = `0.20`
- **ai_enact_weight_modifier**: скрипт, строки 133–140

## Ссылаются

- **Идеологии** (lawgroup_environment: approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]]
- **Идеологии** (lawgroup_environment: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer)|Земельный реформатор (ideology_land_reformer)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer_movement)|Земельный реформатор (ideology_land_reformer_movement)]], [[tgr/Идеологии/Луддит|Луддит]]
- **Идеологии** (lawgroup_environment: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
