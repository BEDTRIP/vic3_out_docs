---
type: concept
description: "Закон «Caliphal Absolutism» — VC 1.13, `law_sublime_porte_absolutism`"
project: vic3
source: vc
aliases: ["Caliphal Absolutism", "law_sublime_porte_absolutism"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_sublime_porte_absolutism
paths: [VC/common/laws/joi_distribution_of_power.txt]
---
# Caliphal Absolutism

Закон · `law_sublime_porte_absolutism` · `common/laws/joi_distribution_of_power.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Распределение власти|Распределение власти]]
- **parent**: [[vanilla/Законы/Автократия|Автократия]]
- **icon**: `gfx/interface/icons/law_icons/sublime_porte_absolutism.dds`
- **progressiveness**: `-100`
- **requires_law_or**: [[vanilla/Законы/Монархия|Монархия]], [[vanilla/Законы/Теократия|Теократия]]
- **on_activate**: скрипт, строки 14–17
- **is_visible**: скрипт, строки 19–21
- **can_enact**: скрипт, строки 23–28
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-headofstate-add|country_legitimacy_headofstate_add]] = `30`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-clout-add|country_legitimacy_govt_total_clout_add]] = `130`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-ideological-incoherence-mult|country_legitimacy_ideological_incoherence_mult]] = `0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-clergymen-pol-str-mult|country_clergymen_pol_str_mult]] = `1`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `300`
- **ai_enact_weight_modifier**: скрипт, строки 40–47
- **ai_impose_chance**: скрипт, строки 49–51
