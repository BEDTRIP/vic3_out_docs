---
type: concept
description: "Закон «Zhou Ritual System» — Mandate of Heaven 1.15, `law_zhou_ritual_system`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Zhou Ritual System", "law_zhou_ritual_system"]
tags: [mandate_of_heaven, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_zhou_ritual_system
paths: [for addon/Mandate of Heaven/common/laws/moh_flavoured_laws.txt]
---
# Zhou Ritual System

Закон · `law_zhou_ritual_system` · `common/laws/moh_flavoured_laws.txt:191`

## Поля

- **group**: [[vanilla/Группы законов/Принципы управления|Принципы управления]]
- **parent**: [[mandate_of_heaven/Законы/Теократия|Теократия]]
- **icon**: `gfx/interface/icons/law_icons/law_zhou_ritual_system.dds`
- **progressiveness**: `0`
- **unlocking_laws**: [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]]
- **is_visible**: скрипт, строки 200–202
- **can_enact**: скрипт, строки 204–206
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-headofstate-add|country_legitimacy_headofstate_add]] = `30`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pol-str-mult|interest_group_ig_devout_pol_str_mult]] = `0.20`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-pol-str-mult|interest_group_ig_landowners_pol_str_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `150`
  - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы C#^m-country-secession-progress-mult|country_secession_progress_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-decree-cost-mult|state_decree_cost_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 218–224
- **ai_enact_weight_modifier**: скрипт, строки 226–238
