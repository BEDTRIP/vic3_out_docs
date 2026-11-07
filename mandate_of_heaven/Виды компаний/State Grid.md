---
type: concept
description: "Вид компании «State Grid» — Mandate of Heaven 1.13, `company_state_grid`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["State Grid", "company_state_grid"]
tags: [mandate_of_heaven, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_state_grid
paths: [for addon/Mandate of Heaven/common/company_types/moh_companies_china.txt]
---
# State Grid

Вид компании · `company_state_grid` · `common/company_types/moh_companies_china.txt:129`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/state_grid.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Электрозаводы|Электрозаводы]]
- **potential**: скрипт, строки 140–142
- **preferred_headquarters**: `STATE_BEIJING`
- **attainable**: скрипт, строки 144–148
- **possible**: скрипт, строки 149–159
- **ai_will_do**: скрипт, строки 160–166
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.1` → [[vanilla/Здания/Электростанции|Электростанции]]
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.1`
- **ai_construction_targets**: скрипт, строки 171–179
- **ai_weight**: скрипт, строки 180–182
