---
type: concept
description: "Закон «12-hour Work Days» — TGR 1.13, `law_token_time_regulations`"
project: vic3
source: tgr
aliases: ["12-hour Work Days", "law_token_time_regulations"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_token_time_regulations
paths: [TheGreatRevision/common/laws/TGR_POLITICS_working_hours.txt]
---
# 12-hour Work Days

Закон · `law_token_time_regulations` · `common/laws/TGR_POLITICS_working_hours.txt:31`

## Поля

- **group**: [[tgr/Группы законов/Working Hours|Working Hours]]
- **icon**: `gfx/interface/icons/law_icons/token_time_regulations.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: пусто
- **disallowing_laws**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы S#^m-state-lower-strata-standard-of-living-add|state_lower_strata_standard_of_living_add]] = `1.0`
- **can_impose**: скрипт, строки 51–53
- **ai_enact_weight_modifier**: скрипт, строки 55–62

## Ссылаются

- **Идеологии** (lawgroup_working_hours: approve): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Реформы|Реформы]]
- **Идеологии** (lawgroup_working_hours: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Коммунизм (ideology_communist)|Коммунизм (ideology_communist)]], [[tgr/Идеологии/Коммунизм (ideology_communist_movement)|Коммунизм (ideology_communist_movement)]], [[tgr/Идеологии/Рабство (идеология)|Рабство (идеология)]]
- **Идеологии** (lawgroup_working_hours: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Рыночный либерализм|Рыночный либерализм]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
