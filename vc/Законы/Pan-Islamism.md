---
type: concept
description: "Закон «Pan-Islamism» — VC 1.13, `law_pan_islamism`"
project: vic3
source: vc
aliases: ["Pan-Islamism", "law_pan_islamism"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_pan_islamism
paths: [VC/common/laws/joi_citizenship.txt]
---
# Pan-Islamism

Закон · `law_pan_islamism` · `common/laws/joi_citizenship.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Гражданство|Гражданство]]
- **parent**: [[vanilla/Законы/Этническое государство|Этническое государство]]
- **icon**: `gfx/interface/icons/law_icons/pan_islamism.dds`
- **progressiveness**: `-100`
- **requires_law_or**: [[vanilla/Законы/Монархия|Монархия]], [[vanilla/Законы/Теократия|Теократия]]
- **on_enact**: скрипт, строки 14–16
- **is_visible**: скрипт, строки 18–23
- **can_enact**: скрипт, строки 25–30
- **modifier**:
  - `country_authority_add` = `300`
  - `state_conversion_mult` = `3`
  - `country_support_separatism_resistance_mult` = `-0.25`
  - `state_migration_pull_unincorporated_mult` = `0.25`
  - `building_training_rate_mult` = `0.33`
  - `unit_morale_loss_mult` = `-0.1`
  - `state_birth_rate_mult` = `0.15`
  - `country_acceptance_state_religion_add` = `100`
  - `country_acceptance_shared_religious_trait_add` = `50`
  - `country_acceptance_shared_religious_trait_group_add` = `0`
  - `country_acceptance_no_shared_religious_trait_add` = `-50`
  - `country_acceptance_primary_culture_add` = `50`
  - `country_acceptance_homeland_add` = `0`
  - `country_acceptance_not_homeland_add` = `0`
  - `country_acceptance_shared_heritage_trait_add` = `25`
  - `country_acceptance_shared_heritage_trait_group_add` = `10`
  - `country_acceptance_no_shared_heritage_trait_add` = `-15`
  - `country_acceptance_shared_language_trait_add` = `10`
  - `country_acceptance_shared_language_trait_group_add` = `5`
  - `country_acceptance_no_shared_language_trait_add` = `-10`
  - `country_acceptance_shared_tradition_trait_add` = `20`
  - `country_acceptance_no_shared_tradition_trait_add` = `0`
- **acceptance_modifier**:
  - `country_standard_of_living_violent_hostility_add` = `-10`
  - `country_standard_of_living_cultural_erasure_add` = `-10`
  - `country_standard_of_living_open_prejudice_add` = `-10`
  - `country_radicalism_increases_violent_hostility_mult` = `0.5`
  - `country_radicalism_increases_cultural_erasure_mult` = `0.5`
  - `country_radicalism_increases_open_prejudice_mult` = `0.5`
  - `country_loyalism_increases_full_acceptance_mult` = `0.2`
  - `country_radicalism_increases_full_acceptance_mult` = `-0.2`
  - `country_allow_voting_violent_hostility_bool` = `no`
  - `country_allow_voting_cultural_erasure_bool` = `no`
  - `country_allow_voting_open_prejudice_bool` = `no`
  - `country_allow_voting_second_rate_citizen_bool` = `no`
  - `country_allow_voting_full_acceptance_bool` = `yes`
  - `country_allow_assimilation_cultural_erasure_bool` = `yes`
  - `country_allow_assimilation_open_prejudice_bool` = `yes`
  - `country_allow_assimilation_second_rate_citizen_bool` = `yes`
  - `country_allow_assimilation_full_acceptance_bool` = `yes`
  - `country_political_strength_violent_hostility_mult` = `-3`
  - `country_political_strength_cultural_erasure_mult` = `-2`
  - `country_political_strength_open_prejudice_mult` = `-1`
  - `country_political_strength_second_rate_citizen_mult` = `-0.5`
  - `country_political_strength_full_acceptance_mult` = `1`
  - `country_wage_violent_hostility_mult` = `-0.5`
  - `country_wage_cultural_erasure_mult` = `-0.5`
  - `country_wage_open_prejudice_mult` = `-0.3`
  - `country_wage_second_rate_citizen_mult` = `-0.2`
  - `country_wage_full_acceptance_mult` = `0.2`
  - `country_qualification_growth_violent_hostility_mult` = `1`
  - `country_qualification_growth_cultural_erasure_mult` = `1`
  - `country_qualification_growth_open_prejudice_mult` = `1`
  - `country_qualification_growth_second_rate_citizen_mult` = `1`
  - `country_qualification_growth_full_acceptance_mult` = `1`
  - `country_disallow_government_work_violent_hostility_bool` = `yes`
  - `country_disallow_government_work_cultural_erasure_bool` = `yes`
  - `country_disallow_government_work_open_prejudice_bool` = `yes`
  - `country_disallow_government_work_second_rate_citizen_bool` = `no`
  - `country_disallow_government_work_full_acceptance_bool` = `no`
- **tax_modifier_very_low**:
  - `tax_heathen_add` = `0.25`
- **tax_modifier_low**:
  - `tax_heathen_add` = `0.5`
- **tax_modifier_medium**:
  - `tax_heathen_add` = `1`
- **tax_modifier_high**:
  - `tax_heathen_add` = `2`
- **tax_modifier_very_high**:
  - `tax_heathen_add` = `3`
- **ai_enact_weight_modifier**: скрипт, строки 137–144
- **ai_impose_chance**: скрипт, строки 146–148
