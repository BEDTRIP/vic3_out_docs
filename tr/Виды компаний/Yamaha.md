---
type: concept
description: "Вид компании «Yamaha» — T&R 1.13, `company_yamaha`"
project: vic3
source: tr
aliases: ["Yamaha", "company_yamaha"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_yamaha
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_entertainment_companies.txt]
---
# Yamaha

Вид компании · `company_yamaha` · `common/company_types/ztr_entertainment_companies.txt:94`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/yamaha.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_TOKAI`
- **building_types**: [[tr/Здания/Instrument Workshops|Instrument Workshops]], [[tr/Здания/Академии искусств|Академии искусств]]
- **extension_building_types**: [[tr/Здания/Производства инструментов|Производства инструментов]], [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **prestige_goods_trigger**: скрипт, строки 112–117
- **potential**: скрипт, строки 118–120
- **attainable**: скрипт, строки 121–128
- **possible**: скрипт, строки 129–139
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
  - `goods_output_elgar_instruments_mult` = `0.1` → [[tr/Товары/Instruments|Instruments]]
- **ai_will_do**: скрипт, строки 144–150
- **ai_construction_targets**: скрипт, строки 151–158
- **ai_weight**: скрипт, строки 159–161
