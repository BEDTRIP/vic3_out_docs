---
type: concept
description: "Закон «Inability to work» — TGR 1.13, `law_retirement_age_inability_to_work`"
project: vic3
audience: agent
source: tgr
aliases: ["Inability to work", "law_retirement_age_inability_to_work"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_retirement_age_inability_to_work
paths: [TheGreatRevision/common/laws/TGR_POLITICS_retirement_age.txt]
---
# Inability to work

Закон · `law_retirement_age_inability_to_work` · `common/laws/TGR_POLITICS_retirement_age.txt:53`

## Поля

- **group**: [[tgr/Группы законов/Retirement Age Policy|Retirement Age Policy]]
- **icon**: `gfx/interface/icons/law_icons/poor_laws.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: [[tgr/Технологии/Демократия|Демократия]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-working-adult-ratio-add|state_working_adult_ratio_add]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-food-security-add|state_food_security_add]] = `0.05`
- **ai_enact_weight_modifier**: скрипт, строки 74–81
- **on_activate**: скрипт, строки 83–91

## Ссылаются

- **Законы** (запрещает закон): [[tgr/Законы/National Institute of Social Security|National Institute of Social Security]], [[tgr/Законы/Social Security Payments|Social Security Payments]]
- **Идеологии** (lawgroup_retirement_age: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_retirement_age: disapprove): [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_retirement_age: neutral): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Пролетарии|Пролетарии]]
