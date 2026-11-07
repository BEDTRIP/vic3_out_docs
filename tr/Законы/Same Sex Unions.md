---
type: concept
description: "Закон «Same Sex Unions» — T&R 1.13, `lgbtq_civil_unions`"
project: vic3
source: tr
aliases: ["Same Sex Unions", "lgbtq_civil_unions"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: lgbtq_civil_unions
paths: [TechRes+Kuromi/t&r/common/laws/ztr_lgbtq_rigths.txt]
---
# Same Sex Unions

Закон · `lgbtq_civil_unions` · `common/laws/ztr_lgbtq_rigths.txt:48`

## Поля

- **group**: [[tr/Группы законов/LGBTQ+ Rights|LGBTQ+ Rights]]
- **icon**: `gfx/interface/icons/law_icons/lgbtq_civil_unions.dds`
- **progressiveness**: `75`
- **disallowing_laws**: [[tr/Законы/Попечительство|Попечительство]]
- **unlocking_technologies**: [[tr/Технологии/Transnational Activism|Transnational Activism]]
- **modifier**:
  - `interest_group_ig_intelligentsia_pol_str_mult` = `0.2`
  - `state_working_adult_ratio_add` = `0.05`
  - `state_radicals_and_loyalists_from_sol_change_mult` = `-0.05`
  - `political_movement_radicalism_from_enactment_disapproval_mult` = `0.1`
- **ai_enact_weight_modifier**: скрипт, строки 70–77

## Ссылаются

- **Идеологии** (lawgroup_lgbtq_rights: disapprove): [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]
- **Идеологии** (lawgroup_lgbtq_rights: neutral): [[tr/Идеологии/Moderate Progressist|Moderate Progressist]]
- **Идеологии** (lawgroup_lgbtq_rights: strongly_approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]
- **Идеологии** (lawgroup_lgbtq_rights: strongly_disapprove): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]]
