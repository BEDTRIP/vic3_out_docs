---
type: concept
description: "Закон «Old Age Pension» — TGR 1.13, `law_minimum_pension`"
project: vic3
source: tgr
aliases: ["Old Age Pension", "law_minimum_pension"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_minimum_pension
paths: [TheGreatRevision/common/laws/TGR_POLITICS_pension.txt]
---
# Old Age Pension

Закон · `law_minimum_pension` · `common/laws/TGR_POLITICS_pension.txt:27`

## Поля

- **group**: [[tgr/Группы законов/Social Security|Social Security]]
- **icon**: `gfx/interface/icons/law_icons/poor_laws.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: [[tgr/Технологии/Демократия|Демократия]]
- **disallowing_laws**: [[tgr/Законы/Нет прав трудящихся|Нет прав трудящихся]], [[tgr/Законы/No Retirement Age|No Retirement Age]]
- **modifier**:
  - `country_institution_cost_institution_pension_mult` = `-1.0`
  - `country_institution_pension_max_investment_add` = `2`
- **institution**: `institution_pension`
- **institution_modifier**:
  - `state_dependent_wage_mult` = `0.10`
  - `country_mass_migration_attraction_mult` = `0.01`
  - `state_tax_collection_mult` = `-0.02`
- **ai_enact_weight_modifier**: скрипт, строки 55–62

## Ссылаются

- **Идеологии** (lawgroup_social_security: approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_social_security: disapprove): [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_social_security: neutral): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Пролетарии|Пролетарии]]
