---
type: concept
description: "Закон «Social Security Payments» — TGR 1.13, `law_medium_pension`"
project: vic3
source: tgr
aliases: ["Social Security Payments", "law_medium_pension"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_medium_pension
paths: [TheGreatRevision/common/laws/TGR_POLITICS_pension.txt]
---
# Social Security Payments

Закон · `law_medium_pension` · `common/laws/TGR_POLITICS_pension.txt:65`

## Поля

- **group**: [[tgr/Группы законов/Social Security|Social Security]]
- **icon**: `gfx/interface/icons/law_icons/wage_controls.dds`
- **progressiveness**: `75`
- **unlocking_technologies**: [[vanilla/Технологии/Профсоюзное движение|Профсоюзное движение]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]], [[tgr/Законы/No Retirement Age|No Retirement Age]], [[tgr/Законы/Inability to work|Inability to work]]
- **modifier**:
  - `country_institution_cost_institution_pension_mult` = `-1.0`
  - `country_institution_pension_max_investment_add` = `2`
- **institution**: `institution_pension`
- **institution_modifier**:
  - `state_dependent_wage_mult` = `0.15`
  - `country_mass_migration_attraction_mult` = `0.02`
  - `state_tax_collection_mult` = `-0.03`
  - `state_dependent_political_participation_add` = `0.02`
- **ai_enact_weight_modifier**: скрипт, строки 95–102

## Ссылаются

- **Идеологии** (lawgroup_social_security: approve): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_social_security: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
