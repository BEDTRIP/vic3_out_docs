---
type: concept
description: "Закон «8-hour Work Days» — TGR 1.13, `law_protected_leisure`"
project: vic3
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
  - `building_throughput_add` = `-0.25`
  - `country_mass_migration_attraction_mult` = `0.25`
  - `state_lower_strata_standard_of_living_add` = `3.0`
  - `state_middle_strata_standard_of_living_add` = `2.0`
- **can_impose**: скрипт, строки 132–134
- **ai_enact_weight_modifier**: скрипт, строки 136–151

## Ссылаются

- **Идеологии** (lawgroup_working_hours: approve): [[tgr/Идеологии/Пролетарии|Пролетарии]]
- **Идеологии** (lawgroup_working_hours: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Реформы|Реформы]]
- **Идеологии** (lawgroup_working_hours: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_working_hours: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Коммунизм (ideology_communist)|Коммунизм (ideology_communist)]], [[tgr/Идеологии/Коммунизм (ideology_communist_movement)|Коммунизм (ideology_communist_movement)]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_working_hours: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Рабство (идеология)|Рабство (идеология)]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]]
