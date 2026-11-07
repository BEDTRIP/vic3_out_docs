---
type: concept
description: "Закон «Scotland Yard» — VC 1.13, `law_scotland_yard`"
project: vic3
source: vc
aliases: ["Scotland Yard", "law_scotland_yard"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_scotland_yard
paths: [VC/common/laws/joi_policing.txt]
---
# Scotland Yard

Закон · `law_scotland_yard` · `common/laws/joi_policing.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Полиция|Полиция]]
- **parent**: [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]]
- **icon**: `gfx/interface/icons/law_icons/scotland_yard.dds`
- **progressiveness**: `75`
- **unlocking_technologies**: [[vanilla/Технологии/Правоохранительные органы|Правоохранительные органы]]
- **is_visible**: скрипт, строки 13–18
- **can_enact**: скрипт, строки 20–25
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-institution-police-max-investment-add|country_institution_police_max_investment_add]] = `2`
  - [[vanilla/движок/Модификаторы C#^m-country-institution-cost-institution-police-mult|country_institution_cost_institution_police_mult]] = `-0.25`
- **institution**: `institution_police`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-mult|state_tax_capacity_mult]] = `0.02`
- **can_impose**: скрипт, строки 38–49
- **ai_will_do**: скрипт, строки 51–53
- **ai_enact_weight_modifier**: скрипт, строки 55–57
