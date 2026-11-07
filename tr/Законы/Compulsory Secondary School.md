---
type: concept
description: "Закон «Compulsory Secondary School» — T&R 1.13, `law_compulsory_secondary_school`"
project: vic3
audience: agent
source: tr
aliases: ["Compulsory Secondary School", "law_compulsory_secondary_school"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_compulsory_secondary_school
paths: [TechRes+Kuromi/t&r/common/laws/ztr_advanced_education.txt]
---
# Compulsory Secondary School

Закон · `law_compulsory_secondary_school` · `common/laws/ztr_advanced_education.txt:22`

## Поля

- **group**: [[tr/Группы законов/Advanced Education Policy|Advanced Education Policy]]
- **icon**: `gfx/interface/icons/law_icons/compulsory_middle_school.dds`
- **progressiveness**: `25`
- **disallowing_laws**: [[tr/Законы/Детский труд разрешён|Детский труд разрешён]], [[tr/Законы/Ограниченный детский труд|Ограниченный детский труд]]
- **unlocking_technologies**: [[tr/Технологии/Social Democracy|Social Democracy]]
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `-0.02`
  - [[vanilla/движок/Модификаторы S#^m-state-pop-qualifications-mult|state_pop_qualifications_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-tech-spread-mult|country_tech_spread_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.05`
- **ai_enact_weight_modifier**: скрипт, строки 40–55

## Ссылаются

- **Идеологии** (lawgroup_advanced_education: approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]], [[tr/Идеологии/Moderate Progressist|Moderate Progressist]], [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]
- **Идеологии** (lawgroup_advanced_education: neutral): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]]
