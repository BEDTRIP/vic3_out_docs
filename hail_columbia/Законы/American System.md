---
type: concept
description: "Закон «American System» — Hail Columbia 1.13, `law_usfp_american_system`"
project: vic3
source: hail_columbia
aliases: ["American System", "law_usfp_american_system"]
tags: [hail_columbia, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_usfp_american_system
paths: [for addon/Hail Columbia/common/laws/usfp_law_variants.txt]
---
# American System

Закон · `law_usfp_american_system` · `common/laws/usfp_law_variants.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Торговая политика|Торговая политика]]
- **parent**: [[hail_columbia/Законы/Протекционизм|Протекционизм]]
- **icon**: `gfx/interface/icons/law_icons/usfp_protectionism_american_system.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[vanilla/Технологии/Фондовая биржа|Фондовая биржа]]
- **is_visible**: скрипт, строки 12–14
- **modifier**:
  - `state_tariff_import_add` = `1.00`
  - `state_tariff_export_add` = `0.00`
  - `state_subvention_export_add` = `0.50`
  - `state_subvention_import_add` = `0.50`
  - `country_leverage_resistance_mult` = `0.35`
- **ai_enact_weight_modifier**: скрипт, строки 28–36
