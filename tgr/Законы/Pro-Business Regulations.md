---
type: concept
description: "Закон «Pro-Business Regulations» — TGR 1.13, `law_salary_competitive_economy`"
project: vic3
source: tgr
aliases: ["Pro-Business Regulations", "law_salary_competitive_economy"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_salary_competitive_economy
paths: [TheGreatRevision/common/laws/TGR_POLITICS_salary_regulation.txt]
---
# Pro-Business Regulations

Закон · `law_salary_competitive_economy` · `common/laws/TGR_POLITICS_salary_regulation.txt:24`

## Поля

- **group**: [[tgr/Группы законов/Salary Regulation|Salary Regulation]]
- **icon**: `gfx/interface/icons/law_icons/laissez_faire.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: пусто
- **modifier**:
  - `country_institution_salary_max_investment_add` = `2`
- **institution**: `institution_salary`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-minimum-wage-mult|building_minimum_wage_mult]] = `-0.03`
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pop-attraction-mult|interest_group_ig_industrialists_pop_attraction_mult]] = `0.10`
- **ai_enact_weight_modifier**: скрипт, строки 48–55

## Ссылаются

- **Идеологии** (lawgroup_salary_regulation: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_salary_regulation: disapprove): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_salary_regulation: neutral): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Пролетарии|Пролетарии]]
