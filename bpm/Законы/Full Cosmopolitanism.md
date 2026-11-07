---
type: concept
description: "Закон «Full Cosmopolitanism» — BPM 1.13, `law_multicultural_upgraded`"
project: vic3
audience: agent
source: bpm
aliases: ["Full Cosmopolitanism", "law_multicultural_upgraded"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_multicultural_upgraded
paths: [BPM/common/laws/BPM_citizenship.txt]
---
# Full Cosmopolitanism

Закон · `law_multicultural_upgraded` · `common/laws/BPM_citizenship.txt:41`

## Поля

- **group**: [[vanilla/Группы законов/Гражданство|Гражданство]]
- **parent**: [[bpm/Законы/Космополитизм|Космополитизм]]
- **icon**: `gfx/interface/icons/law_icons/multicultural.dds`
- **progressiveness**: `100`
- **unlocking_laws**: [[bpm/Законы/Запрет рабства|Запрет рабства]]
- **unlocking_technologies**: [[vanilla/Технологии/Права человека|Права человека]]
- **is_visible**: скрипт, строки 57–59
- **on_enact**: скрипт, строки 61–75
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-primary-culture-add|country_acceptance_primary_culture_add]] = `100`
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-resistance-mult|country_support_separatism_resistance_mult]] = `0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-strength-mult|country_support_separatism_strength_mult]] = `-0.5`
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-cultural-majority-mult|state_pop_support_movement_cultural_majority_mult]] = `-0.75`
  - [[vanilla/движок/Модификаторы S#^m-state-pop-support-movement-cultural-minority-mult|state_pop_support_movement_cultural_minority_mult]] = `-0.75`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-heritage-trait-add|country_acceptance_shared_heritage_trait_add]] = `60`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-heritage-trait-group-add|country_acceptance_shared_heritage_trait_group_add]] = `50`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-heritage-trait-add|country_acceptance_no_shared_heritage_trait_add]] = `40`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-language-trait-add|country_acceptance_shared_language_trait_add]] = `50`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-language-trait-group-add|country_acceptance_shared_language_trait_group_add]] = `40`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-language-trait-add|country_acceptance_no_shared_language_trait_add]] = `25`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-tradition-trait-add|country_acceptance_shared_tradition_trait_add]] = `10`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-tradition-trait-add|country_acceptance_no_shared_tradition_trait_add]] = `5`
  - [[vanilla/движок/Модификаторы C#^m-country-primary-culture-fervor-from-laws-add|country_primary_culture_fervor_from_laws_add]] = `-25`
- **acceptance_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-violent-hostility-bool|country_allow_voting_violent_hostility_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-cultural-erasure-bool|country_allow_voting_cultural_erasure_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-open-prejudice-bool|country_allow_voting_open_prejudice_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-second-rate-citizen-bool|country_allow_voting_second_rate_citizen_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-full-acceptance-bool|country_allow_voting_full_acceptance_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-cultural-erasure-bool|country_allow_assimilation_cultural_erasure_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-open-prejudice-bool|country_allow_assimilation_open_prejudice_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-second-rate-citizen-bool|country_allow_assimilation_second_rate_citizen_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-full-acceptance-bool|country_allow_assimilation_full_acceptance_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-violent-hostility-mult|country_wage_violent_hostility_mult]] = `-0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-cultural-erasure-mult|country_wage_cultural_erasure_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-open-prejudice-mult|country_wage_open_prejudice_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-violent-hostility-bool|country_disallow_military_work_violent_hostility_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-cultural-erasure-bool|country_disallow_military_work_cultural_erasure_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-open-prejudice-bool|country_disallow_military_work_open_prejudice_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-second-rate-citizen-bool|country_disallow_military_work_second_rate_citizen_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-full-acceptance-bool|country_disallow_military_work_full_acceptance_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-violent-hostility-bool|country_disallow_government_work_violent_hostility_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-cultural-erasure-bool|country_disallow_government_work_cultural_erasure_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-open-prejudice-bool|country_disallow_government_work_open_prejudice_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-second-rate-citizen-bool|country_disallow_government_work_second_rate_citizen_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-full-acceptance-bool|country_disallow_government_work_full_acceptance_bool]] = `no`
- **ai_enact_weight_modifier**: скрипт, строки 136–143
