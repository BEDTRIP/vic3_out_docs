---
type: concept
description: "Вид компании «Benz & Cie» — VC 1.15, `company_benz_cie`"
project: vic3
audience: agent
source: vc
aliases: ["Benz & Cie", "company_benz_cie"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_benz_cie
paths: [VC/common/company_types/joi_companies.txt]
---
# Benz & Cie

Вид компании · `company_benz_cie` · `common/company_types/joi_companies.txt:79`

## Поля

- **icon**: `gfx/interface/icons/joi_icons/benz_cie.png`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_RHINELAND`, `STATE_WURTTEMBERG`, `STATE_BAVARIA`
- **building_types**: [[vc/Здания/Моторные заводы|Моторные заводы]], [[vc/Здания/Автомобильные заводы|Автомобильные заводы]]
- **extension_building_types**: [[vc/Здания/Производства инструментов|Производства инструментов]]
- **possible_prestige_goods**: `prestige_good_benz_car`
- **potential**: скрипт, строки 100–102
- **attainable**: скрипт, строки 104–113
- **possible**: скрипт, строки 115–129
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы G#^m-goods-output-tanks-mult|goods_output_tanks_mult]] = `0.1` → [[vanilla/Товары/Танки|Танки]]
  - `unit_combat_unit_type_light_tanks_offense_mult` = `0.25`
  - [[vanilla/движок/Модификаторы G#^m-goods-output-automobiles-mult|goods_output_automobiles_mult]] = `0.1` → [[vanilla/Товары/Автомобили|Автомобили]]
- **ai_will_do**: скрипт, строки 137–142
- **ai_construction_targets**: скрипт, строки 144–151
- **ai_weight**: скрипт, строки 153–155
