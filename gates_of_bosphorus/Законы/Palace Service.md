---
type: concept
description: "Закон «Palace Service» — Gates of Bosphorus 1.15, `law_gbbf_palace_service`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Palace Service", "law_gbbf_palace_service"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_gbbf_palace_service
paths: [for addon/gatesofbosphorus/common/laws/0_gbbf_internal_security.txt]
---
# Palace Service

Закон · `law_gbbf_palace_service` · `common/laws/0_gbbf_internal_security.txt:1`

## Поля

- **icon**: `gfx/interface/icons/law_icons/secret_police.dds`
- **group**: [[vanilla/Группы законов/Внутренняя безопасность|Внутренняя безопасность]]
- **parent**: [[vanilla/Законы/Тайная полиция|Тайная полиция]]
- **progressiveness**: `-25`
- **is_visible**: скрипт, строки 7–9
- **can_impose**: скрипт, строки 11–13
- **unlocking_technologies**: [[vanilla/Технологии/Бюрократия (технология)|Бюрократия (технология)]]
- **disallowing_laws**: [[vanilla/Законы/Защита свободы слова|Защита свободы слова]], [[vanilla/Законы/Гарантия свобод|Гарантия свобод]]
- **on_activate**: скрипт, строки 24–26
- **on_deactivate**: скрипт, строки 28–38
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-suppression-attraction-factor|country_suppression_attraction_factor]] = `-0.10`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-add|political_movement_radicalism_add]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-coup-resistance-add|country_coup_resistance_add]] = `0.75`
  - `country_enable_exile_to_libya_bool` = `yes`
- **ai_enact_weight_modifier**: скрипт, строки 49–51
