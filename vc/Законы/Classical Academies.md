---
type: concept
description: "Закон «Classical Academies» — VC 1.13, `law_classical_learning`"
project: vic3
source: vc
aliases: ["Classical Academies", "law_classical_learning"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_classical_learning
paths: [VC/common/laws/joi_education_system.txt]
---
# Classical Academies

Закон · `law_classical_learning` · `common/laws/joi_education_system.txt:65`

## Поля

- **group**: [[vanilla/Группы законов/Система образования|Система образования]]
- **parent**: [[vanilla/Законы/Частные школы|Частные школы]]
- **icon**: `gfx/interface/icons/law_icons/private_schools.dds`
- **progressiveness**: `-25`
- **requires_law_or**: [[vanilla/Законы/Крепостное право|Крепостное право]], [[vc/Законы/Imperial Examination|Imperial Examination]]
- **is_visible**: скрипт, строки 78–80
- **can_enact**: скрипт, строки 82–84
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-institution-cost-institution-schools-mult|country_institution_cost_institution_schools_mult]] = `-0.5`
  - [[vanilla/движок/Модификаторы B#^m-building-university-throughput-add|building_university_throughput_add]] = `-0.25` → [[vanilla/Здания/Университеты|Университеты]]
  - [[vanilla/движок/Модификаторы B#^m-building-government-administration-throughput-add|building_government_administration_throughput_add]] = `0.25` → [[vanilla/Здания/Правительственные ведомства|Правительственные ведомства]]
- **institution**: `institution_schools`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-conversion-mult|state_conversion_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.0025`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pol-str-mult|interest_group_ig_landowners_pol_str_mult]] = `0.3`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `-10`
- **ai_will_do**: скрипт, строки 100–102
- **ai_enact_weight_modifier**: скрипт, строки 104–106
