---
type: concept
description: "Закон «Devolved Taxation» — Hail Columbia 1.13, `law_usfp_devolved_taxation`"
project: vic3
source: hail_columbia
aliases: ["Devolved Taxation", "law_usfp_devolved_taxation"]
tags: [hail_columbia, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_usfp_devolved_taxation
paths: [for addon/Hail Columbia/common/laws/usfp_law_variants.txt]
---
# Devolved Taxation

Закон · `law_usfp_devolved_taxation` · `common/laws/usfp_law_variants.txt:120`

## Поля

- **group**: [[vanilla/Группы законов/Налогообложение|Налогообложение]]
- **parent**: [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]]
- **progressiveness**: `-100`
- **icon**: `gfx/interface/icons/law_icons/law_usfp_devolved_taxation.dds`
- **is_visible**: скрипт, строки 127–129
- **modifier**:
  - `state_bureaucracy_population_base_cost_factor_mult` = `-0.20`
  - `state_tax_capacity_add` = `25`
  - `state_tax_capacity_mult` = `0.25`
  - `country_consumption_tax_cost_mult` = `-0.25`
  - `country_bureaucracy_investment_cost_factor_mult` = `-0.10`
- **tax_modifier_very_low**:
  - `tax_consumption_add` = `0.10`
  - `tax_land_add` = `0.04`
- **tax_modifier_low**:
  - `tax_consumption_add` = `0.15`
  - `tax_land_add` = `0.08`
- **tax_modifier_medium**:
  - `tax_consumption_add` = `0.20`
  - `tax_land_add` = `0.12`
- **tax_modifier_high**:
  - `tax_consumption_add` = `0.25`
  - `tax_land_add` = `0.16`
- **tax_modifier_very_high**:
  - `tax_consumption_add` = `0.30`
  - `tax_land_add` = `0.20`
- **ai_will_do**: скрипт, строки 165–167
- **ai_enact_weight_modifier**: скрипт, строки 169–176
