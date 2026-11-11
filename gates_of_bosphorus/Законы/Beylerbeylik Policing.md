---
type: concept
description: "Закон «Beylerbeylik Policing» — Gates of Bosphorus 1.15, `law_gbbf_beylerbeylik_policing`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Beylerbeylik Policing", "law_gbbf_beylerbeylik_policing"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_gbbf_beylerbeylik_policing
paths: [for addon/gatesofbosphorus/common/laws/0_gbbf_policing.txt]
---
# Beylerbeylik Policing

Закон · `law_gbbf_beylerbeylik_policing` · `common/laws/0_gbbf_policing.txt:1`

## Поля

- **icon**: `gfx/interface/icons/law_icons/revolutionary_guard.dds`
- **group**: [[vanilla/Группы законов/Полиция|Полиция]]
- **parent**: [[vanilla/Законы/Местная полиция|Местная полиция]]
- **progressiveness**: `-50`
- **is_visible**: скрипт, строки 7–9
- **disallowing_laws**: [[vanilla/Законы/Парламентская республика|Парламентская республика]], [[vanilla/Законы/Президентская республика|Президентская республика]], [[vanilla/Законы/Советская республика|Советская республика]]
- **can_impose**: скрипт, строки 17–19
- **on_activate**: скрипт, строки 21–23
- **institution**: `institution_police`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-aristocrats-pol-str-mult|country_aristocrats_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-officers-pol-str-mult|country_officers_pol_str_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-decree-cost-mult|state_decree_cost_mult]] = `0.10`
- **on_deactivate**: скрипт, строки 33–35
- **ai_will_do**: скрипт, строки 37–39
- **ai_enact_weight_modifier**: скрипт, строки 41–43
- **ai_impose_chance**: скрипт, строки 45–47
