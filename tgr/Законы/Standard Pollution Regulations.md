---
type: concept
description: "Закон «Standard Pollution Regulations» — TGR 1.15, `law_standard_environment_regulations`"
project: vic3
audience: agent
source: tgr
aliases: ["Standard Pollution Regulations", "law_standard_environment_regulations"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_standard_environment_regulations
paths: [TheGreatRevision/common/laws/TGR_POLITICS_environment_regulations.txt]
---
# Standard Pollution Regulations

Закон · `law_standard_environment_regulations` · `common/laws/TGR_POLITICS_environment_regulations.txt:69`

## Поля

- **group**: [[tgr/Группы законов/Pollution Regulations|Pollution Regulations]]
- **icon**: `gfx/interface/icons/law_icons/colonial_resettlement.dds`
- **progressiveness**: `75`
- **unlocking_technologies**: [[tgr/Технологии/Цивилизаторская миссия|Цивилизаторская миссия]]
- **institution**: `institution_environment`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.04`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `0.02`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `-0.02`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-logging-throughput-add|building_group_bg_logging_throughput_add]] = `-0.02`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-oil-extraction-throughput-add|building_group_bg_oil_extraction_throughput_add]] = `-0.02`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-manufacturing-throughput-add|building_group_bg_manufacturing_throughput_add]] = `-0.02`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-rural-folk-pol-str-mult|interest_group_ig_rural_folk_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-rural-folk-pop-attraction-mult|interest_group_ig_rural_folk_pop_attraction_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-farmers-pol-str-mult|country_farmers_pol_str_mult]] = `0.15`
- **ai_enact_weight_modifier**: скрипт, строки 96–103

## Ссылаются

- **Идеологии** (lawgroup_environment: approve): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer)|Земельный реформатор (ideology_land_reformer)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer_movement)|Земельный реформатор (ideology_land_reformer_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Луддит|Луддит]]
- **Идеологии** (lawgroup_environment: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
