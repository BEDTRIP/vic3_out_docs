---
type: concept
description: "Закон «Ministerial Council» — Gates of Bosphorus 1.15, `law_ministerial_council`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Ministerial Council", "law_ministerial_council"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_ministerial_council
paths: [for addon/gatesofbosphorus/common/laws/0_gbbf_governance_principles.txt]
---
# Ministerial Council

Закон · `law_ministerial_council` · `common/laws/0_gbbf_governance_principles.txt:69`

## Поля

- **icon**: `gfx/interface/icons/law_icons/organic_regulation.dds`
- **group**: [[vanilla/Группы законов/Распределение власти|Распределение власти]]
- **parent**: [[vanilla/Законы/Олигархия|Олигархия]]
- **progressiveness**: `0`
- **is_visible**: скрипт, строки 75–80
- **on_activate**: скрипт, строки 82–87
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-headofstate-add|country_legitimacy_headofstate_add]] = `10`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-clout-add|country_legitimacy_govt_total_clout_add]] = `120`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-size-add|country_legitimacy_govt_size_add]] = `2`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-ideological-incoherence-mult|country_legitimacy_ideological_incoherence_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-aristocrats-pol-str-mult|country_aristocrats_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-capitalists-pol-str-mult|country_capitalists_pol_str_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `100`
- **can_impose**: скрипт, строки 101–103
- **on_deactivate**: скрипт, строки 105–116
- **ai_will_do**: скрипт, строки 118–122
- **ai_enact_weight_modifier**: скрипт, строки 124–131
- **ai_impose_chance**: скрипт, строки 133–135
