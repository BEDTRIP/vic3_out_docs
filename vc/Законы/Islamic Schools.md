---
type: concept
description: "Закон «Islamic Schools» — VC 1.13, `law_madrasa`"
project: vic3
source: vc
aliases: ["Islamic Schools", "law_madrasa"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_madrasa
paths: [VC/common/laws/joi_education_system.txt]
---
# Islamic Schools

Закон · `law_madrasa` · `common/laws/joi_education_system.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Система образования|Система образования]]
- **parent**: [[vanilla/Законы/Религиозные школы|Религиозные школы]]
- **icon**: `gfx/interface/icons/law_icons/religious_schools.dds`
- **progressiveness**: `-50`
- **requires_law_or**: [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]], [[vanilla/Законы/Система миллетов|Система миллетов]], [[vanilla/Законы/Люди Писания|Люди Писания]]
- **is_visible**: скрипт, строки 15–21
- **can_enact**: скрипт, строки 23–29
- **on_activate**: скрипт, строки 31–40
- **modifier**:
  - `country_institution_cost_institution_schools_mult` = `-0.5`
  - `building_university_throughput_add` = `-0.2` → [[vanilla/Здания/Университеты|Университеты]]
  - `country_loyalism_increases_full_acceptance_mult` = `0.1`
- **institution**: `institution_schools`
- **institution_modifier**:
  - `state_conversion_mult` = `0.5`
  - `state_education_access_wealth_add` = `0.0025`
  - `interest_group_ig_devout_pol_str_mult` = `0.3`
  - `country_weekly_innovation_max_add` = `-5`
- **ai_will_do**: скрипт, строки 56–58
- **ai_enact_weight_modifier**: скрипт, строки 60–62
