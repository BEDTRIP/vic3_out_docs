---
type: concept
description: "Закон «Tribal Identity» — Hail Columbia 1.13, `law_usfp_tribal_identity`"
project: vic3
source: hail_columbia
aliases: ["Tribal Identity", "law_usfp_tribal_identity"]
tags: [hail_columbia, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_usfp_tribal_identity
paths: [for addon/Hail Columbia/common/laws/usfp_native_laws.txt]
---
# Tribal Identity

Закон · `law_usfp_tribal_identity` · `common/laws/usfp_native_laws.txt:117`

## Поля

- **group**: [[vanilla/Группы законов/Гражданство|Гражданство]]
- **parent**: [[vanilla/Законы/Подданство|Подданство]]
- **icon**: `gfx/interface/icons/law_icons/cultural_exclusion.dds`
- **progressiveness**: `25`
- **unlocking_laws**: [[vanilla/Законы/Вождество|Вождество]], [[vanilla/Законы/Совет старейшин|Совет старейшин]]
- **is_visible**: скрипт, строки 129–134
- **on_enact**: скрипт, строки 136–150
- **can_impose**: скрипт, строки 152–154
- **ai_will_do**: скрипт, строки 156–158
- **modifier**:
  - `state_assimilation_mult` = `-0.25`
  - `country_support_separatism_resistance_mult` = `-0.5`
  - `country_support_separatism_strength_mult` = `-0.5`
  - `country_acceptance_primary_culture_add` = `100`
  - `country_acceptance_homeland_add` = `30`
  - `country_acceptance_not_homeland_add` = `0`
  - `country_acceptance_shared_heritage_trait_add` = `20`
  - `country_acceptance_shared_heritage_trait_group_add` = `15`
  - `country_acceptance_no_shared_heritage_trait_add` = `0`
  - `country_acceptance_shared_language_trait_add` = `20`
  - `country_acceptance_shared_language_trait_group_add` = `15`
  - `country_acceptance_no_shared_language_trait_add` = `0`
  - `country_acceptance_shared_tradition_trait_add` = `25`
  - `country_acceptance_no_shared_tradition_trait_add` = `0`
- **acceptance_modifier**:
  - `country_radicalism_increases_violent_hostility_mult` = `0.2`
  - `country_radicalism_increases_cultural_erasure_mult` = `0.1`
  - `country_loyalism_increases_second_rate_citizen_mult` = `0.05`
  - `country_loyalism_increases_full_acceptance_mult` = `0.1`
  - `country_allow_voting_violent_hostility_bool` = `no`
  - `country_allow_voting_cultural_erasure_bool` = `no`
  - `country_allow_voting_open_prejudice_bool` = `yes`
  - `country_voting_power_open_prejudice_mult` = `-0.25`
  - `country_allow_voting_second_rate_citizen_bool` = `yes`
  - `country_allow_voting_full_acceptance_bool` = `yes`
  - `country_allow_assimilation_cultural_erasure_bool` = `yes`
  - `country_allow_assimilation_open_prejudice_bool` = `yes`
  - `country_allow_assimilation_second_rate_citizen_bool` = `yes`
  - `country_allow_assimilation_full_acceptance_bool` = `yes`
  - `country_political_strength_violent_hostility_mult` = `-0.4`
  - `country_political_strength_cultural_erasure_mult` = `-0.3`
  - `country_political_strength_open_prejudice_mult` = `-0.2`
  - `country_political_strength_second_rate_citizen_mult` = `-0.1`
  - `country_wage_violent_hostility_mult` = `-0.4`
  - `country_wage_cultural_erasure_mult` = `-0.3`
  - `country_wage_open_prejudice_mult` = `-0.2`
  - `country_wage_second_rate_citizen_mult` = `-0.1`
  - `country_qualification_growth_violent_hostility_mult` = `-0.5`
  - `country_qualification_growth_cultural_erasure_mult` = `-0.3`
  - `country_qualification_growth_open_prejudice_mult` = `-0.1`
  - `country_disallow_military_work_violent_hostility_bool` = `yes`
  - `country_disallow_military_work_cultural_erasure_bool` = `no`
  - `country_disallow_military_work_open_prejudice_bool` = `no`
  - `country_disallow_military_work_second_rate_citizen_bool` = `no`
  - `country_disallow_military_work_full_acceptance_bool` = `no`
  - `country_disallow_government_work_violent_hostility_bool` = `yes`
  - `country_disallow_government_work_cultural_erasure_bool` = `yes`
  - `country_disallow_government_work_open_prejudice_bool` = `no`
  - `country_disallow_government_work_second_rate_citizen_bool` = `no`
  - `country_disallow_government_work_full_acceptance_bool` = `no`
- **ai_enact_weight_modifier**: скрипт, строки 233–235
