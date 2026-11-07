---
type: concept
description: "Вид компании «Whirlpool» — T&R 1.13, `company_whirlpool`"
project: vic3
source: tr
aliases: ["Whirlpool", "company_whirlpool"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_whirlpool
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_furniture_companies.txt]
---
# Whirlpool

Вид компании · `company_whirlpool` · `common/company_types/ztr_furniture_companies.txt:321`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_whirlpool.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_MICHIGAN`
- **building_types**: [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Производства инструментов|Производства инструментов]]
- **potential**: скрипт, строки 332–334
- **attainable**: скрипт, строки 335–342
- **possible**: скрипт, строки 343–353
- **prosperity_modifier**:
  - `goods_output_homeappliances_mult` = `0.05` → [[tr/Товары/Home Appliances|Home Appliances]]
  - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.1` → [[tr/Здания/Пищевые производства|Пищевые производства]]
  - [[vanilla/движок/Модификаторы S#^m-state-standard-of-living-add|state_standard_of_living_add]] = `0.25`
- **ai_will_do**: скрипт, строки 359–365
- **ai_construction_targets**: скрипт, строки 366–373
- **ai_weight**: скрипт, строки 374–376
