---
type: concept
description: "Закон «Minimal Pollution Regulations» — TGR 1.13, `law_minimum_environment_regulations`"
project: vic3
source: tgr
aliases: ["Minimal Pollution Regulations", "law_minimum_environment_regulations"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_minimum_environment_regulations
paths: [TheGreatRevision/common/laws/TGR_POLITICS_environment_regulations.txt]
---
# Minimal Pollution Regulations

Закон · `law_minimum_environment_regulations` · `common/laws/TGR_POLITICS_environment_regulations.txt:26`

## Поля

- **group**: [[tgr/Группы законов/Pollution Regulations|Pollution Regulations]]
- **icon**: `gfx/interface/icons/law_icons/interventionism.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[tgr/Технологии/Хинин|Хинин]]
- **institution**: `institution_environment`
- **institution_modifier**:
  - `state_pollution_reduction_health_mult` = `-0.02`
  - `building_group_bg_mining_throughput_add` = `-0.01`
  - `building_group_bg_logging_throughput_add` = `-0.01`
  - `building_group_bg_oil_extraction_throughput_add` = `-0.01`
  - `building_group_bg_manufacturing_throughput_add` = `-0.01`
  - `country_farmers_pol_str_mult` = `0.10`
  - `interest_group_ig_rural_folk_pol_str_mult` = `0.02`
  - `interest_group_ig_rural_folk_pop_attraction_mult` = `0.05`
- **ai_will_do**: скрипт, строки 52–57
- **ai_enact_weight_modifier**: скрипт, строки 59–66

## Ссылаются

- **Идеологии** (lawgroup_environment: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]]
- **Идеологии** (lawgroup_environment: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer)|Земельный реформатор (ideology_land_reformer)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer_movement)|Земельный реформатор (ideology_land_reformer_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Луддит|Луддит]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
