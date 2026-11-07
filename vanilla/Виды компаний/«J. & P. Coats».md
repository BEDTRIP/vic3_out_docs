---
type: concept
description: "Вид компании ««J. & P. Coats»» — ваниль 1.13, `company_j_p_coats`"
project: vic3
source: vanilla
aliases: ["«J. & P. Coats»", "J. & P. Coats", "company_j_p_coats"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_j_p_coats
paths: [.vanillaVIC3/common/company_types/00_companies_great_britain.txt]
---
# «J. & P. Coats»

Вид компании · `company_j_p_coats` · `common/company_types/00_companies_great_britain.txt:2`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/gb_jp_coats.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOWLANDS`
- **building_types**: [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **possible_prestige_goods**: `prestige_good_generic_clothes`
- **prestige_goods_trigger**: скрипт, строки 22–27
- **potential**: скрипт, строки 29–31
- **attainable**: скрипт, строки 33–39
- **possible**: скрипт, строки 41–51
- **prosperity_modifier**:
  - `building_textile_mill_throughput_add` = `0.15` → [[vanilla/Здания/Текстильные фабрики|Текстильные фабрики]]
  - `building_cotton_plantation_throughput_add` = `0.05` → [[vanilla/Здания/Плантации хлопка|Плантации хлопка]]
- **ai_will_do**: скрипт, строки 58–64
- **ai_construction_targets**: скрипт, строки 66–73
- **ai_weight**: скрипт, строки 75–77
