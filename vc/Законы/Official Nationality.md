---
type: concept
description: "Закон «Official Nationality» — VC 1.13, `law_official_nationalism`"
project: vic3
source: vc
aliases: ["Official Nationality", "law_official_nationalism"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_official_nationalism
paths: [VC/common/laws/joi_citizenship.txt]
---
# Official Nationality

Закон · `law_official_nationalism` · `common/laws/joi_citizenship.txt:151`

## Поля

- **group**: [[vanilla/Группы законов/Гражданство|Гражданство]]
- **parent**: [[vanilla/Законы/Подданство|Подданство]]
- **icon**: `gfx/interface/icons/law_icons/imperial_subjecthood.dds`
- **progressiveness**: `-50`
- **requires_law_or**: [[vanilla/Законы/Монархия|Монархия]], [[vanilla/Законы/Социальная монархия|Социальная монархия]]
- **on_enact**: скрипт, строки 164–166
- **is_visible**: скрипт, строки 168–174
- **can_enact**: скрипт, строки 176–181
- **modifier**:
  - `country_authority_add` = `300`
  - `state_conversion_mult` = `1`
  - `country_support_separatism_resistance_mult` = `-0.25`
  - `country_support_separatism_strength_mult` = `-0.25`
  - `state_birth_rate_mult` = `0.2`
  - `state_building_conscription_center_max_level_add` = `25`
  - `state_peasants_education_access_add` = `-0.1`
  - `state_pop_support_movement_royalist_absolutist_mult` = `0.5`
  - `state_pop_support_movement_religious_majority_mult` = `0.5`
  - `country_acceptance_state_religion_add` = `25`
  - `country_acceptance_shared_religious_trait_add` = `10`
  - `country_acceptance_shared_religious_trait_group_add` = `-10`
  - `country_acceptance_no_shared_religious_trait_add` = `-25`
  - `country_acceptance_primary_culture_add` = `100`
  - `country_acceptance_homeland_add` = `40`
  - `country_acceptance_not_homeland_add` = `0`
  - `country_acceptance_shared_heritage_trait_add` = `30`
  - `country_acceptance_shared_heritage_trait_group_add` = `10`
  - `country_acceptance_no_shared_heritage_trait_add` = `0`
  - `country_acceptance_shared_language_trait_add` = `30`
  - `country_acceptance_shared_language_trait_group_add` = `10`
  - `country_acceptance_no_shared_language_trait_add` = `0`
  - `country_acceptance_shared_tradition_trait_add` = `30`
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
  - `country_allow_conversion_violent_hostility_bool` = `yes`
  - `country_allow_conversion_cultural_erasure_bool` = `yes`
  - `country_allow_conversion_open_prejudice_bool` = `yes`
  - `country_allow_conversion_second_rate_citizen_bool` = `yes`
  - `country_allow_conversion_full_acceptance_bool` = `yes`
- **ai_enact_weight_modifier**: скрипт, строки 276–283
- **ai_impose_chance**: скрипт, строки 285–287
