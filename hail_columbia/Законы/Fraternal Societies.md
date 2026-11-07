---
type: concept
description: "Закон «Fraternal Societies» — Hail Columbia 1.13, `law_usfp_fraternities`"
project: vic3
source: hail_columbia
aliases: ["Fraternal Societies", "law_usfp_fraternities"]
tags: [hail_columbia, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_usfp_fraternities
paths: [for addon/Hail Columbia/common/laws/usfp_native_laws.txt]
---
# Fraternal Societies

Закон · `law_usfp_fraternities` · `common/laws/usfp_native_laws.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Бюрократия (группа законов)|Бюрократия (группа законов)]]
- **parent**: [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]]
- **icon**: `gfx/interface/icons/law_icons/usfp_law_fraternities.dds`
- **progressiveness**: `-25`
- **is_visible**: скрипт, строки 8–13
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-loyalism-increases-full-acceptance-mult|state_loyalism_increases_full_acceptance_mult]] = `0.10`
- **disallowing_laws**: [[vanilla/Законы/Советская республика|Советская республика]]
- **unlocking_laws**: [[vanilla/Законы/Вождество|Вождество]]
- **ai_will_do**: скрипт, строки 38–40
- **ai_enact_weight_modifier**: скрипт, строки 42–49
