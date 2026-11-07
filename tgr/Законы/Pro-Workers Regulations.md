---
type: concept
description: "Закон «Pro-Workers Regulations» — TGR 1.13, `law_salary_national_contract`"
project: vic3
audience: agent
source: tgr
aliases: ["Pro-Workers Regulations", "law_salary_national_contract"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_salary_national_contract
paths: [TheGreatRevision/common/laws/TGR_POLITICS_salary_regulation.txt]
---
# Pro-Workers Regulations

Закон · `law_salary_national_contract` · `common/laws/TGR_POLITICS_salary_regulation.txt:92`

## Поля

- **group**: [[tgr/Группы законов/Salary Regulation|Salary Regulation]]
- **icon**: `gfx/interface/icons/law_icons/worker_protections.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[tgr/Технологии/Права человека|Права человека]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]]
- **modifier**:
  - `country_institution_salary_max_investment_add` = `2`
- **institution**: `institution_salary`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-minimum-wage-mult|building_minimum_wage_mult]] = `0.03`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-trade-unions-pol-str-mult|interest_group_ig_trade_unions_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-trade-unions-pop-attraction-mult|interest_group_ig_trade_unions_pop_attraction_mult]] = `0.10`
- **on_activate**: скрипт, строки 121–123
- **on_deactivate**: скрипт, строки 125–127
- **ai_enact_weight_modifier**: скрипт, строки 129–136

## Ссылаются

- **Идеологии** (lawgroup_salary_regulation: approve): [[tgr/Идеологии/Пролетарии|Пролетарии]]
- **Идеологии** (lawgroup_salary_regulation: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_salary_regulation: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_salary_regulation: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_salary_regulation: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
