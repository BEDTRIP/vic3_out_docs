---
type: concept
description: "Закон «Unregulated Working Hours» — TGR 1.15, `law_unregulated_work_time`"
project: vic3
audience: agent
source: tgr
aliases: ["Unregulated Working Hours", "law_unregulated_work_time"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_unregulated_work_time
paths: [TheGreatRevision/common/laws/TGR_POLITICS_working_hours.txt]
---
# Unregulated Working Hours

Закон · `law_unregulated_work_time` · `common/laws/TGR_POLITICS_working_hours.txt:5`

## Поля

- **group**: [[tgr/Группы законов/Working Hours|Working Hours]]
- **icon**: `gfx/interface/icons/law_icons/unregulated_work_time.dds`
- **progressiveness**: `0`
- **modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `-0.25`
- **can_impose**: скрипт, строки 17–19
- **ai_enact_weight_modifier**: скрипт, строки 21–28

## Ссылаются

- **Идеологии** (lawgroup_working_hours: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Рабство (идеология)|Рабство (идеология)]]
- **Идеологии** (lawgroup_working_hours: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Пролетарство|Пролетарство]], [[tgr/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_working_hours: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_working_hours: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Коммунизм (ideology_communist_movement)|Коммунизм (ideology_communist_movement)]]
