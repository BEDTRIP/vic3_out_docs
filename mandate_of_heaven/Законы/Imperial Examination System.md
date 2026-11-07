---
type: concept
description: "Закон «Imperial Examination System» — Mandate of Heaven 1.13, `law_imperial_examinations`"
project: vic3
source: mandate_of_heaven
aliases: ["Imperial Examination System", "law_imperial_examinations"]
tags: [mandate_of_heaven, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_imperial_examinations
paths: [for addon/Mandate of Heaven/common/laws/moh_flavoured_laws.txt]
---
# Imperial Examination System

Закон · `law_imperial_examinations` · `common/laws/moh_flavoured_laws.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Бюрократия (группа законов)|Бюрократия (группа законов)]]
- **parent**: [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]]
- **icon**: `gfx/interface/icons/law_icons/keju.dds`
- **progressiveness**: `0`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-mult|state_tax_capacity_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-tech-spread-mult|country_tech_spread_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pop-attraction-mult|interest_group_ig_landowners_pop_attraction_mult]] = `0.05`
- **is_visible**: скрипт, строки 19–23
- **can_enact**: скрипт, строки 25–27
- **on_enact**: скрипт, строки 29–42
- **ai_enact_weight_modifier**: скрипт, строки 44–46
