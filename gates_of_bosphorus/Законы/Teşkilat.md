---
type: concept
description: "Закон «Teşkilat» — Gates of Bosphorus 1.15, `law_gbbf_teshkilat`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Teşkilat", "law_gbbf_teshkilat"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_gbbf_teshkilat
paths: [for addon/gatesofbosphorus/common/laws/0_gbbf_internal_security.txt]
---
# Teşkilat

Закон · `law_gbbf_teshkilat` · `common/laws/0_gbbf_internal_security.txt:54`

## Поля

- **icon**: `gfx/interface/icons/law_icons/secret_police.dds`
- **group**: [[vanilla/Группы законов/Внутренняя безопасность|Внутренняя безопасность]]
- **parent**: [[vanilla/Законы/Тайная полиция|Тайная полиция]]
- **progressiveness**: `-25`
- **is_visible**: скрипт, строки 60–62
- **can_impose**: скрипт, строки 64–66
- **unlocking_technologies**: [[vanilla/Технологии/Центральный архив|Центральный архив]]
- **disallowing_laws**: [[vanilla/Законы/Защита свободы слова|Защита свободы слова]], [[vanilla/Законы/Гарантия свобод|Гарантия свобод]]
- **on_activate**: скрипт, строки 77–79
- **on_deactivate**: скрипт, строки 81–91
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.25`
  - `country_enable_exile_to_libya_bool` = `yes`
- **institution**: `institution_home_affairs`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-suppression-attraction-factor|country_suppression_attraction_factor]] = `-0.10`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-add|political_movement_radicalism_add]] = `-0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-resistance-mult|country_support_separatism_resistance_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-support-separatism-strength-mult|country_support_separatism_strength_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-amenability-add|country_amenability_add]] = `3`
  - [[vanilla/движок/Модификаторы C#^m-country-coup-resistance-add|country_coup_resistance_add]] = `0.75`
- **ai_enact_weight_modifier**: скрипт, строки 108–110
