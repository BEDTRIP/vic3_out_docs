---
type: concept
description: "Вид компании «Rolls-Royce» — VC 1.15, `company_rolls_royce`"
project: vic3
audience: agent
source: vc
aliases: ["Rolls-Royce", "company_rolls_royce"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_rolls_royce
paths: [VC/common/company_types/joi_companies.txt]
---
# Rolls-Royce

Вид компании · `company_rolls_royce` · `common/company_types/joi_companies.txt:7293`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/rolls_royce.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LANCASHIRE`, `STATE_HOME_COUNTIES`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **possible_prestige_goods**: `prestige_good_rr_engines`
- **potential**: скрипт, строки 7314–7316
- **attainable**: скрипт, строки 7318–7324
- **possible**: скрипт, строки 7326–7342
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-army-offense-mult|unit_army_offense_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-aeroplanes-mult|goods_output_aeroplanes_mult]] = `0.1` → [[vanilla/Товары/Аэропланы|Аэропланы]]
  - [[vanilla/движок/Модификаторы G#^m-goods-output-engines-mult|goods_output_engines_mult]] = `0.15` → [[vanilla/Товары/Двигатели|Двигатели]]
- **ai_will_do**: скрипт, строки 7350–7355
- **ai_construction_targets**: скрипт, строки 7357–7364
- **ai_weight**: скрипт, строки 7366–7368
