---
type: concept
description: "Вид компании «Unilever» — T&R 1.13, `company_unilever`"
project: vic3
audience: agent
source: tr
aliases: ["Unilever", "company_unilever"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_unilever
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_cosmetics_companies.txt]
---
# Unilever

Вид компании · `company_unilever` · `common/company_types/ztr_cosmetics_companies.txt:226`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/british_unilever.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufactering_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[tr/Здания/Заводы синтетики|Заводы синтетики]], [[tr/Здания/Пищевые производства|Пищевые производства]]
- **extension_building_types**: [[tr/Здания/Стеклозаводы|Стеклозаводы]]
- **possible_prestige_goods**: `prestige_good_hygiene_cosmetics`
- **potential**: скрипт, строки 243–245
- **attainable**: скрипт, строки 246–253
- **possible**: скрипт, строки 254–267
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-tea-plantations-throughput-add|building_group_bg_tea_plantations_throughput_add]] = `0.1`
  - `building_aircraft_industry_throughput_add` = `0.05` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы S#^m-state-food-security-add|state_food_security_add]] = `0.05`
- **ai_will_do**: скрипт, строки 273–279
- **ai_construction_targets**: скрипт, строки 280–293
- **ai_weight**: скрипт, строки 294–296
