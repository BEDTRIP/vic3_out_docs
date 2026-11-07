---
type: concept
description: "Закон «Scribal Bureaucrats» — Gates of Bosphorus 1.13, `law_scribal_bureaucrats`"
project: vic3
source: gates_of_bosphorus
aliases: ["Scribal Bureaucrats", "law_scribal_bureaucrats"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_scribal_bureaucrats
paths: [for addon/gatesofbosphorus/common/laws/gbbf_bureaucracy.txt]
---
# Scribal Bureaucrats

Закон · `law_scribal_bureaucrats` · `common/laws/gbbf_bureaucracy.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Бюрократия (группа законов)|Бюрократия (группа законов)]]
- **icon**: `gfx/interface/icons/law_icons/scribal_bureaucrats.dds`
- **parent**: [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]]
- **progressiveness**: `-50`
- **is_visible**: скрипт, строки 8–10
- **disallowing_laws**: [[vanilla/Законы/Советская республика|Советская республика]]
- **modifier**:
  - `state_incorporation_speed_mult` = `-0.25`
  - `state_bureaucracy_population_base_cost_factor_mult` = `-0.10`
  - `country_institution_size_change_speed_mult` = `-0.25`
  - `country_aristocrats_pol_str_mult` = `0.10`
  - `country_bureaucrats_pol_str_mult` = `0.50`
- **on_activate**: скрипт, строки 24–26
- **on_enact**: скрипт, строки 28–36
- **on_deactivate**: скрипт, строки 38–40
- **ai_will_do**: скрипт, строки 42–47
- **ai_enact_weight_modifier**: скрипт, строки 49–56
