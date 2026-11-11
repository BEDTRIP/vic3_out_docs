---
type: concept
description: "Закон «8-hour Work Days» — TGR 1.15, `law_protected_leisure`"
project: vic3
audience: agent
source: tgr
aliases: ["8-hour Work Days", "law_protected_leisure"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_protected_leisure
paths: [TheGreatRevision/common/laws/TGR_POLITICS_working_hours.txt]
---
# 8-hour Work Days

Закон · `law_protected_leisure` · `common/laws/TGR_POLITICS_working_hours.txt:110`

## Поля

- **group**: [[tgr/Группы законов/Working Hours|Working Hours]]
- **icon**: `gfx/interface/icons/law_icons/right_to_rest.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[tgr/Технологии/Права человека|Права человека]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]]
- **modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-lower-strata-standard-of-living-add|state_lower_strata_standard_of_living_add]] = `3.0`
  - [[vanilla/движок/Модификаторы S#^m-state-middle-strata-standard-of-living-add|state_middle_strata_standard_of_living_add]] = `2.0`
- **can_impose**: скрипт, строки 132–134
- **ai_enact_weight_modifier**: скрипт, строки 136–151

## Ссылаются

- **Идеологии** (lawgroup_working_hours: approve): [[tgr/Идеологии/Пролетарство|Пролетарство]]
- **Идеологии** (lawgroup_working_hours: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_working_hours: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_working_hours: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Коммунизм (ideology_communist_movement)|Коммунизм (ideology_communist_movement)]], [[tgr/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_working_hours: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Рабство (идеология)|Рабство (идеология)]]
