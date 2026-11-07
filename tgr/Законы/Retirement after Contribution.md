---
type: concept
description: "Закон «Retirement after Contribution» — TGR 1.13, `law_retirement_after_contribution`"
project: vic3
audience: agent
source: tgr
aliases: ["Retirement after Contribution", "law_retirement_after_contribution"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_retirement_after_contribution
paths: [TheGreatRevision/common/laws/TGR_POLITICS_retirement_age.txt]
---
# Retirement after Contribution

Закон · `law_retirement_after_contribution` · `common/laws/TGR_POLITICS_retirement_age.txt:94`

## Поля

- **group**: [[tgr/Группы законов/Retirement Age Policy|Retirement Age Policy]]
- **icon**: `gfx/interface/icons/law_icons/wage_controls.dds`
- **progressiveness**: `75`
- **unlocking_technologies**: [[vanilla/Технологии/Профсоюзное движение|Профсоюзное движение]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-working-adult-ratio-add|state_working_adult_ratio_add]] = `-0.10`
  - [[vanilla/движок/Модификаторы S#^m-state-food-security-add|state_food_security_add]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `0.05`
- **ai_enact_weight_modifier**: скрипт, строки 115–122
- **on_activate**: скрипт, строки 124–132

## Ссылаются

- **Законы** (запрещает закон): [[tgr/Законы/National Institute of Social Security|National Institute of Social Security]]
- **Идеологии** (lawgroup_retirement_age: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_retirement_age: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
