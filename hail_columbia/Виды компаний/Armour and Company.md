---
type: concept
description: "Вид компании «Armour and Company» — Hail Columbia 1.13, `company_usfp_armours`"
project: vic3
source: hail_columbia
aliases: ["Armour and Company", "company_usfp_armours"]
tags: [hail_columbia, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_usfp_armours
paths: [for addon/Hail Columbia/common/company_types/usfp_companies.txt]
---
# Armour and Company

Вид компании · `company_usfp_armours` · `common/company_types/usfp_companies.txt:546`

## Поля

- **icon**: `gfx/interface/icons/company_icons/usfp_company_armours.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILLINOIS`, `STATE_NEBRASKA`
- **building_types**: [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]], [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **potential**: скрипт, строки 566–575
- **possible**: скрипт, строки 577–590
- **prosperity_modifier**:
  - `building_livestock_ranch_throughput_add` = `0.15` → [[vanilla/Здания/Животноводческие фермы|Животноводческие фермы]]
  - `interest_group_ig_industrialists_pol_str_mult` = `0.20`
  - `building_group_bg_ranching_laborers_mortality_mult` = `0.02`
  - `state_radicals_from_political_movements_mult` = `0.10`
- **ai_will_do**: скрипт, строки 599–611
- **ai_construction_targets**: скрипт, строки 613–623
- **ai_weight**: скрипт, строки 625–627
