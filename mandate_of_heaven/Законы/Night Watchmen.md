---
type: concept
description: "Закон «Night Watchmen» — Mandate of Heaven 1.13, `law_night_watchmen`"
project: vic3
source: mandate_of_heaven
aliases: ["Night Watchmen", "law_night_watchmen"]
tags: [mandate_of_heaven, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_night_watchmen
paths: [for addon/Mandate of Heaven/common/laws/moh_flavoured_laws.txt]
---
# Night Watchmen

Закон · `law_night_watchmen` · `common/laws/moh_flavoured_laws.txt:49`

## Поля

- **group**: [[vanilla/Группы законов/Полиция|Полиция]]
- **parent**: [[vanilla/Законы/Нет полиции|Нет полиции]]
- **icon**: `gfx/interface/icons/law_icons/law_night_watchmen.dds`
- **progressiveness**: `0`
- **modifier**:
  - `interest_group_ig_petty_bourgeoisie_pol_str_mult` = `0.02`
  - `state_turmoil_effects_mult` = `-0.05`
- **is_visible**: скрипт, строки 62–66
- **can_enact**: скрипт, строки 68–70
- **ai_will_do**: скрипт, строки 73–75
- **ai_enact_weight_modifier**: скрипт, строки 77–84
