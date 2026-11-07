---
type: concept
description: "Вид компании «IKEA» — T&R 1.13, `company_ikea`"
project: vic3
source: tr
aliases: ["IKEA", "company_ikea"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ikea
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_furniture_companies.txt]
---
# IKEA

Вид компании · `company_ikea` · `common/company_types/ztr_furniture_companies.txt:13`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swedish_ikea.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SVEALAND`
- **building_types**: [[tr/Здания/Мебельные фабрики|Мебельные фабрики]], [[tr/Здания/Лесозаготовки|Лесозаготовки]], [[tr/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[tr/Здания/Академии искусств|Академии искусств]], [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]]
- **possible_prestige_goods**: `prestige_good_ikea_furniture`
- **potential**: скрипт, строки 32–34
- **attainable**: скрипт, строки 35–42
- **possible**: скрипт, строки 43–53
- **prosperity_modifier**:
  - `goods_output_furniture_mult` = `0.1` → [[vanilla/Товары/Мебель|Мебель]]
  - `state_standard_of_living_add` = `0.25`
- **ai_will_do**: скрипт, строки 58–64
- **ai_construction_targets**: скрипт, строки 65–72
- **ai_weight**: скрипт, строки 73–75
