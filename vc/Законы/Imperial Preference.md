---
type: concept
description: "Закон «Imperial Preference» — VC 1.13, `law_imperial_preference`"
project: vic3
source: vc
aliases: ["Imperial Preference", "law_imperial_preference"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_imperial_preference
paths: [VC/common/laws/joi_trade_policy.txt]
---
# Imperial Preference

Закон · `law_imperial_preference` · `common/laws/joi_trade_policy.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Торговая политика|Торговая политика]]
- **parent**: [[vanilla/Законы/Протекционизм|Протекционизм]]
- **icon**: `gfx/interface/icons/law_icons/imperial_preference.dds`
- **progressiveness**: `0`
- **is_visible**: скрипт, строки 9–22
- **can_enact**: скрипт, строки 24–29
- **modifier**:
  - `state_tariff_import_add` = `0.75`
  - `state_tariff_export_add` = `0.75`
  - `state_subvention_export_add` = `0.60`
  - `state_subvention_import_add` = `0.40`
  - `country_leverage_resistance_mult` = `0.5`
  - `state_export_advantage_mult` = `0.25`
- **ai_will_do**: скрипт, строки 40–42
- **ai_enact_weight_modifier**: скрипт, строки 44–46
