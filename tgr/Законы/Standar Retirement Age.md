---
type: concept
description: "Закон «Standar Retirement Age» — TGR 1.13, `law_retirement_standard_retirement_age`"
project: vic3
audience: agent
source: tgr
aliases: ["Standar Retirement Age", "law_retirement_standard_retirement_age"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_retirement_standard_retirement_age
paths: [TheGreatRevision/common/laws/TGR_POLITICS_retirement_age.txt]
---
# Standar Retirement Age

Закон · `law_retirement_standard_retirement_age` · `common/laws/TGR_POLITICS_retirement_age.txt:135`

## Поля

- **group**: [[tgr/Группы законов/Retirement Age Policy|Retirement Age Policy]]
- **icon**: `gfx/interface/icons/law_icons/old_age_pension.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[tgr/Технологии/Права человека|Права человека]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-working-adult-ratio-add|state_working_adult_ratio_add]] = `-0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-food-security-add|state_food_security_add]] = `0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `0.10`
- **ai_enact_weight_modifier**: скрипт, строки 156–163
- **on_activate**: скрипт, строки 165–173

## Ссылаются

- **Идеологии** (lawgroup_retirement_age: approve): [[tgr/Идеологии/Пролетарии|Пролетарии]]
- **Идеологии** (lawgroup_retirement_age: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_retirement_age: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_retirement_age: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_retirement_age: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
