---
type: concept
description: "Закон «Full Cosmopolitanism» — BPM 1.13, `law_multicultural_upgraded`"
project: vic3
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
  - `country_acceptance_primary_culture_add` = `100`
  - `country_support_separatism_resistance_mult` = `0.5`
  - `country_support_separatism_strength_mult` = `-0.5`
  - `state_assimilation_mult` = `-0.25`
  - `state_pop_support_movement_cultural_majority_mult` = `-0.75`
  - `state_pop_support_movement_cultural_minority_mult` = `-0.75`
  - `country_acceptance_shared_heritage_trait_add` = `60`
  - `country_acceptance_shared_heritage_trait_group_add` = `50`
  - `country_acceptance_no_shared_heritage_trait_add` = `40`
  - `country_acceptance_shared_language_trait_add` = `50`
  - `country_acceptance_shared_language_trait_group_add` = `40`
  - `country_acceptance_no_shared_language_trait_add` = `25`
  - `country_acceptance_shared_tradition_trait_add` = `10`
  - `country_acceptance_no_shared_tradition_trait_add` = `5`
  - `country_primary_culture_fervor_from_laws_add` = `-25`
- **acceptance_modifier**:
  - `country_allow_voting_violent_hostility_bool` = `yes`
  - `country_allow_voting_cultural_erasure_bool` = `yes`
  - `country_allow_voting_open_prejudice_bool` = `yes`
  - `country_allow_voting_second_rate_citizen_bool` = `yes`
  - `country_allow_voting_full_acceptance_bool` = `yes`
  - `country_allow_assimilation_cultural_erasure_bool` = `yes`
  - `country_allow_assimilation_open_prejudice_bool` = `yes`
  - `country_allow_assimilation_second_rate_citizen_bool` = `yes`
  - `country_allow_assimilation_full_acceptance_bool` = `yes`
  - `country_wage_violent_hostility_mult` = `-0.2`
  - `country_wage_cultural_erasure_mult` = `-0.1`
  - `country_wage_open_prejudice_mult` = `-0.05`
  - `country_disallow_military_work_violent_hostility_bool` = `no`
  - `country_disallow_military_work_cultural_erasure_bool` = `no`
  - `country_disallow_military_work_open_prejudice_bool` = `no`
  - `country_disallow_military_work_second_rate_citizen_bool` = `no`
  - `country_disallow_military_work_full_acceptance_bool` = `no`
  - `country_disallow_government_work_violent_hostility_bool` = `no`
  - `country_disallow_government_work_cultural_erasure_bool` = `no`
  - `country_disallow_government_work_open_prejudice_bool` = `no`
  - `country_disallow_government_work_second_rate_citizen_bool` = `no`
  - `country_disallow_government_work_full_acceptance_bool` = `no`
- **ai_enact_weight_modifier**: скрипт, строки 136–143
