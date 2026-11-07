---
type: concept
description: "Закон «Tribal Identity» — Hail Columbia 1.13, `law_usfp_tribal_identity`"
project: vic3
audience: agent
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
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-resistance-mult|country_support_separatism_resistance_mult]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-strength-mult|country_support_separatism_strength_mult]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-primary-culture-add|country_acceptance_primary_culture_add]] = `100`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-homeland-add|country_acceptance_homeland_add]] = `30`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-not-homeland-add|country_acceptance_not_homeland_add]] = `0`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-heritage-trait-add|country_acceptance_shared_heritage_trait_add]] = `20`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-heritage-trait-group-add|country_acceptance_shared_heritage_trait_group_add]] = `15`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-heritage-trait-add|country_acceptance_no_shared_heritage_trait_add]] = `0`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-language-trait-add|country_acceptance_shared_language_trait_add]] = `20`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-language-trait-group-add|country_acceptance_shared_language_trait_group_add]] = `15`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-language-trait-add|country_acceptance_no_shared_language_trait_add]] = `0`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-tradition-trait-add|country_acceptance_shared_tradition_trait_add]] = `25`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-tradition-trait-add|country_acceptance_no_shared_tradition_trait_add]] = `0`
- **acceptance_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-radicalism-increases-violent-hostility-mult|country_radicalism_increases_violent_hostility_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-radicalism-increases-cultural-erasure-mult|country_radicalism_increases_cultural_erasure_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-loyalism-increases-second-rate-citizen-mult|country_loyalism_increases_second_rate_citizen_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-loyalism-increases-full-acceptance-mult|country_loyalism_increases_full_acceptance_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-violent-hostility-bool|country_allow_voting_violent_hostility_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-cultural-erasure-bool|country_allow_voting_cultural_erasure_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-open-prejudice-bool|country_allow_voting_open_prejudice_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-voting-power-open-prejudice-mult|country_voting_power_open_prejudice_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-second-rate-citizen-bool|country_allow_voting_second_rate_citizen_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-voting-full-acceptance-bool|country_allow_voting_full_acceptance_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-cultural-erasure-bool|country_allow_assimilation_cultural_erasure_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-open-prejudice-bool|country_allow_assimilation_open_prejudice_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-second-rate-citizen-bool|country_allow_assimilation_second_rate_citizen_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-assimilation-full-acceptance-bool|country_allow_assimilation_full_acceptance_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-political-strength-violent-hostility-mult|country_political_strength_violent_hostility_mult]] = `-0.4`
  - [[vanilla/движок/Модификаторы C#^m-country-political-strength-cultural-erasure-mult|country_political_strength_cultural_erasure_mult]] = `-0.3`
  - [[vanilla/движок/Модификаторы C#^m-country-political-strength-open-prejudice-mult|country_political_strength_open_prejudice_mult]] = `-0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-political-strength-second-rate-citizen-mult|country_political_strength_second_rate_citizen_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-violent-hostility-mult|country_wage_violent_hostility_mult]] = `-0.4`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-cultural-erasure-mult|country_wage_cultural_erasure_mult]] = `-0.3`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-open-prejudice-mult|country_wage_open_prejudice_mult]] = `-0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-wage-second-rate-citizen-mult|country_wage_second_rate_citizen_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-qualification-growth-violent-hostility-mult|country_qualification_growth_violent_hostility_mult]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-qualification-growth-cultural-erasure-mult|country_qualification_growth_cultural_erasure_mult]] = `-0.3`
  - [[vanilla/движок/Модификаторы C#^m-country-qualification-growth-open-prejudice-mult|country_qualification_growth_open_prejudice_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-violent-hostility-bool|country_disallow_military_work_violent_hostility_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-cultural-erasure-bool|country_disallow_military_work_cultural_erasure_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-open-prejudice-bool|country_disallow_military_work_open_prejudice_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-second-rate-citizen-bool|country_disallow_military_work_second_rate_citizen_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-military-work-full-acceptance-bool|country_disallow_military_work_full_acceptance_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-violent-hostility-bool|country_disallow_government_work_violent_hostility_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-cultural-erasure-bool|country_disallow_government_work_cultural_erasure_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-open-prejudice-bool|country_disallow_government_work_open_prejudice_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-second-rate-citizen-bool|country_disallow_government_work_second_rate_citizen_bool]] = `no`
  - [[vanilla/движок/Модификаторы C#^m-country-disallow-government-work-full-acceptance-bool|country_disallow_government_work_full_acceptance_bool]] = `no`
- **ai_enact_weight_modifier**: скрипт, строки 233–235
