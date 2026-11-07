---
type: concept
description: "Закон «Standard Salary Regulations» — TGR 1.13, `law_salary_minimum_safety`"
project: vic3
audience: agent
source: tgr
aliases: ["Standard Salary Regulations", "law_salary_minimum_safety"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_salary_minimum_safety
paths: [TheGreatRevision/common/laws/TGR_POLITICS_salary_regulation.txt]
---
# Standard Salary Regulations

Закон · `law_salary_minimum_safety` · `common/laws/TGR_POLITICS_salary_regulation.txt:58`

## Поля

- **group**: [[tgr/Группы законов/Salary Regulation|Salary Regulation]]
- **icon**: `gfx/interface/icons/law_icons/wage_controls.dds`
- **progressiveness**: `75`
- **unlocking_technologies**: [[vanilla/Технологии/Профсоюзное движение|Профсоюзное движение]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]]
- **modifier**:
  - `country_institution_salary_max_investment_add` = `2`
- **institution**: `institution_salary`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-minimum-wage-mult|building_minimum_wage_mult]] = `0.02`
- **ai_enact_weight_modifier**: скрипт, строки 82–89

## Ссылаются

- **Идеологии** (lawgroup_salary_regulation: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_salary_regulation: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
