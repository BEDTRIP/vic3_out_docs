---
type: concept
description: "Закон «No Compulsory Secondary School» — T&R 1.13, `law_no_compulsory_secondary_school`"
project: vic3
source: tr
aliases: ["No Compulsory Secondary School", "law_no_compulsory_secondary_school"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_compulsory_secondary_school
paths: [TechRes+Kuromi/t&r/common/laws/ztr_advanced_education.txt]
---
# No Compulsory Secondary School

Закон · `law_no_compulsory_secondary_school` · `common/laws/ztr_advanced_education.txt:1`

## Поля

- **group**: [[tr/Группы законов/Advanced Education Policy|Advanced Education Policy]]
- **icon**: `gfx/interface/icons/law_icons/no_compulsory_secondary_school.dds`
- **progressiveness**: `0`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-expected-sol-from-literacy|state_expected_sol_from_literacy]] = `-1`
  - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `-0.1`
- **ai_enact_weight_modifier**: скрипт, строки 10–19

## Ссылаются

- **Идеологии** (lawgroup_advanced_education: approve): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]]
- **Идеологии** (lawgroup_advanced_education: disapprove): [[tr/Идеологии/Moderate Progressist|Moderate Progressist]]
- **Идеологии** (lawgroup_advanced_education: neutral): [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]
- **Идеологии** (lawgroup_advanced_education: strongly_disapprove): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]
