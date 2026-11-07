---
type: concept
description: "Закон «Imperial Examination» — VC 1.13, `law_imperial_examination`"
project: vic3
source: vc
aliases: ["Imperial Examination", "law_imperial_examination"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_imperial_examination
paths: [VC/common/laws/joi_bureaucracy.txt]
---
# Imperial Examination

Закон · `law_imperial_examination` · `common/laws/joi_bureaucracy.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Бюрократия (группа законов)|Бюрократия (группа законов)]]
- **parent**: [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]]
- **icon**: `gfx/interface/icons/law_icons/imperial_examination.dds`
- **progressiveness**: `-25`
- **requires_law_or**: [[vanilla/Законы/Монархия|Монархия]], [[vanilla/Законы/Социальная монархия|Социальная монархия]]
- **is_visible**: скрипт, строки 14–16
- **can_enact**: скрипт, строки 18–20
- **on_enact**: скрипт, строки 22–35
- **modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pop-attraction-mult|interest_group_ig_landowners_pop_attraction_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pop-attraction-mult|interest_group_ig_devout_pop_attraction_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-peasants-pol-str-mult|country_peasants_pol_str_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-mult|state_tax_capacity_mult]] = `0.33`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-add|political_movement_radicalism_add]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-tech-spread-mult|country_tech_spread_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `100`
- **ai_will_do**: скрипт, строки 48–50
- **ai_enact_weight_modifier**: скрипт, строки 52–54

## Ссылаются

- **Законы** (requires_law_or): [[vc/Законы/Classical Academies|Classical Academies]]
