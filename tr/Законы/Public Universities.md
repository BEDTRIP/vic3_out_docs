---
type: concept
description: "Закон «Public Universities» — T&R 1.13, `law_public_universities`"
project: vic3
source: tr
aliases: ["Public Universities", "law_public_universities"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_public_universities
paths: [TechRes+Kuromi/t&r/common/laws/ztr_advanced_education.txt]
---
# Public Universities

Закон · `law_public_universities` · `common/laws/ztr_advanced_education.txt:58`

## Поля

- **group**: [[tr/Группы законов/Advanced Education Policy|Advanced Education Policy]]
- **icon**: `gfx/interface/icons/law_icons/public_universities.dds`
- **progressiveness**: `50`
- **disallowing_laws**: [[tr/Законы/Детский труд разрешён|Детский труд разрешён]], [[tr/Законы/Ограниченный детский труд|Ограниченный детский труд]], [[vanilla/Законы/Религиозные школы|Религиозные школы]]
- **unlocking_technologies**: [[tr/Технологии/Social Democracy|Social Democracy]]
- **modifier**:
  - `building_office_throughput_add` = `0.05` → [[tr/Здания/Offices|Offices]]
  - `building_university_throughput_add` = `0.1` → [[vanilla/Здания/Университеты|Университеты]]
  - `country_tech_spread_mult` = `0.33`
  - `state_expected_sol_from_literacy` = `1`
  - `state_standard_of_living_add` = `0.5`
  - `state_turmoil_effects_mult` = `-0.1`
  - `state_birth_rate_mult` = `-0.02`
- **ai_enact_weight_modifier**: скрипт, строки 79–100

## Ссылаются

- **Идеологии** (lawgroup_advanced_education: disapprove): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]]
- **Идеологии** (lawgroup_advanced_education: neutral): [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]
- **Идеологии** (lawgroup_advanced_education: strongly_approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]], [[tr/Идеологии/Moderate Progressist|Moderate Progressist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]
