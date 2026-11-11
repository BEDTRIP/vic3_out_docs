---
type: concept
description: "Закон «Military Governate» — Gates of Bosphorus 1.15, `law_gbbf_military_administration`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Military Governate", "law_gbbf_military_administration"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_gbbf_military_administration
paths: [for addon/gatesofbosphorus/common/laws/0_gbbf_governance_principles.txt]
---
# Military Governate

Закон · `law_gbbf_military_administration` · `common/laws/0_gbbf_governance_principles.txt:138`

## Поля

- **group**: [[vanilla/Группы законов/Принципы управления|Принципы управления]]
- **parent**: [[vanilla/Законы/Монархия|Монархия]]
- **icon**: `gfx/interface/icons/law_icons/law_gbbf_military_administration.dds`
- **progressiveness**: `0`
- **disallowing_laws**: [[vanilla/Законы/Анархия|Анархия]]
- **is_visible**: скрипт, строки 150–152
- **can_impose**: скрипт, строки 154–156
- **on_activate**: скрипт, строки 158–161
- **on_deactivate**: скрипт, строки 163–166
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-headofstate-add|country_legitimacy_headofstate_add]] = `10`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-ideological-incoherence-mult|country_legitimacy_ideological_incoherence_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.50`
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `1`
  - [[vanilla/движок/Модификаторы C#^m-country-aristocrats-pol-str-mult|country_aristocrats_pol_str_mult]] = `-0.50`
  - [[vanilla/движок/Модификаторы C#^m-country-soldiers-pol-str-mult|country_soldiers_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `100`
- **ai_will_do**: скрипт, строки 178–180
- **ai_enact_weight_modifier**: скрипт, строки 182–189
- **ai_impose_chance**: скрипт, строки 191–193
