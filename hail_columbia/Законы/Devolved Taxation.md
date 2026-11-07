---
type: concept
description: "Закон «Devolved Taxation» — Hail Columbia 1.13, `law_usfp_devolved_taxation`"
project: vic3
audience: agent
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
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `-0.20`
  - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `25`
  - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-mult|state_tax_capacity_mult]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-consumption-tax-cost-mult|country_consumption_tax_cost_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-investment-cost-factor-mult|country_bureaucracy_investment_cost_factor_mult]] = `-0.10`
- **tax_modifier_very_low**:
  - [[vanilla/движок/Модификаторы T#^m-tax-consumption-add|tax_consumption_add]] = `0.10`
  - [[vanilla/движок/Модификаторы T#^m-tax-land-add|tax_land_add]] = `0.04`
- **tax_modifier_low**:
  - [[vanilla/движок/Модификаторы T#^m-tax-consumption-add|tax_consumption_add]] = `0.15`
  - [[vanilla/движок/Модификаторы T#^m-tax-land-add|tax_land_add]] = `0.08`
- **tax_modifier_medium**:
  - [[vanilla/движок/Модификаторы T#^m-tax-consumption-add|tax_consumption_add]] = `0.20`
  - [[vanilla/движок/Модификаторы T#^m-tax-land-add|tax_land_add]] = `0.12`
- **tax_modifier_high**:
  - [[vanilla/движок/Модификаторы T#^m-tax-consumption-add|tax_consumption_add]] = `0.25`
  - [[vanilla/движок/Модификаторы T#^m-tax-land-add|tax_land_add]] = `0.16`
- **tax_modifier_very_high**:
  - [[vanilla/движок/Модификаторы T#^m-tax-consumption-add|tax_consumption_add]] = `0.30`
  - [[vanilla/движок/Модификаторы T#^m-tax-land-add|tax_land_add]] = `0.20`
- **ai_will_do**: скрипт, строки 165–167
- **ai_enact_weight_modifier**: скрипт, строки 169–176
