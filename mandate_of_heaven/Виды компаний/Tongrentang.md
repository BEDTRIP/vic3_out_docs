---
type: concept
description: "Вид компании «Tongrentang» — Mandate of Heaven 1.15, `company_tongrentang`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Tongrentang", "company_tongrentang"]
tags: [mandate_of_heaven, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_tongrentang
paths: [for addon/Mandate of Heaven/common/company_types/moh_companies_china.txt]
---
# Tongrentang

Вид компании · `company_tongrentang` · `common/company_types/moh_companies_china.txt:356`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/tongrentang.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_farm_wheat.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Маковые плантации|Маковые плантации]]
- **preferred_headquarters**: `STATE_BEIJING`
- **extension_building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **potential**: скрипт, строки 367–369
- **attainable**: скрипт, строки 370–376
- **possible**: скрипт, строки 377–385
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-opium-plantation-throughput-add|building_opium_plantation_throughput_add]] = `0.1` → [[vanilla/Здания/Маковые плантации|Маковые плантации]]
  - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.5`
- **ai_weight**: скрипт, строки 391–393
- **ai_construction_targets**: скрипт, строки 394–402
- **ai_will_do**: скрипт, строки 403–409
