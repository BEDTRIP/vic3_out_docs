---
type: concept
description: "Закон «National Institute of Social Security» — TGR 1.13, `law_modern_pension`"
project: vic3
source: tgr
aliases: ["National Institute of Social Security", "law_modern_pension"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_modern_pension
paths: [TheGreatRevision/common/laws/TGR_POLITICS_pension.txt]
---
# National Institute of Social Security

Закон · `law_modern_pension` · `common/laws/TGR_POLITICS_pension.txt:105`

## Поля

- **group**: [[tgr/Группы законов/Social Security|Social Security]]
- **icon**: `gfx/interface/icons/law_icons/old_age_pension.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[tgr/Технологии/Права человека|Права человека]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]], [[tgr/Законы/No Retirement Age|No Retirement Age]], [[tgr/Законы/Inability to work|Inability to work]], [[tgr/Законы/Retirement after Contribution|Retirement after Contribution]]
- **modifier**:
  - `country_institution_cost_institution_pension_mult` = `-1.0`
  - `country_institution_pension_max_investment_add` = `2`
- **institution**: `institution_pension`
- **institution_modifier**:
  - `state_dependent_wage_mult` = `0.20`
  - `country_mass_migration_attraction_mult` = `0.05`
  - `state_tax_collection_mult` = `-0.04`
  - `state_dependent_political_participation_add` = `0.05`
- **on_activate**: скрипт, строки 137–139
- **on_deactivate**: скрипт, строки 141–143
- **ai_enact_weight_modifier**: скрипт, строки 145–152

## Ссылаются

- **Идеологии** (lawgroup_social_security: approve): [[tgr/Идеологии/Пролетарии|Пролетарии]]
- **Идеологии** (lawgroup_social_security: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_social_security: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_social_security: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_social_security: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
