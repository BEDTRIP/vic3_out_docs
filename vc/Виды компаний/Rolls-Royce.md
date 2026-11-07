---
type: concept
description: "Вид компании «Rolls-Royce» — VC 1.13, `company_rolls_royce`"
project: vic3
source: vc
aliases: ["Rolls-Royce", "company_rolls_royce"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rolls_royce
paths: [VC/common/company_types/joi_companies.txt]
---
# Rolls-Royce

Вид компании · `company_rolls_royce` · `common/company_types/joi_companies.txt:7290`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/rolls_royce.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LANCASHIRE`, `STATE_HOME_COUNTIES`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: `prestige_good_rr_engines`
- **potential**: скрипт, строки 7311–7313
- **attainable**: скрипт, строки 7315–7321
- **possible**: скрипт, строки 7323–7339
- **prosperity_modifier**:
  - `unit_army_offense_mult` = `0.05`
  - `goods_output_aeroplanes_mult` = `0.1` → [[vanilla/Товары/Аэропланы|Аэропланы]]
  - `goods_output_engines_mult` = `0.15` → [[vanilla/Товары/Двигатели|Двигатели]]
- **ai_will_do**: скрипт, строки 7347–7352
- **ai_construction_targets**: скрипт, строки 7354–7361
- **ai_weight**: скрипт, строки 7363–7365
