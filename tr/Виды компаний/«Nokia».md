---
type: concept
description: "Вид компании ««Nokia»» — T&R 1.13, `company_nokia`"
project: vic3
source: tr
aliases: ["«Nokia»", "Nokia", "company_nokia"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nokia
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_europe.txt]
replaces: "[[vanilla/Виды компаний/«Nokia»]]"
---
# «Nokia»

Вид компании · `company_nokia` · `common/company_types/ztr_companies_europe.txt:81` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_types**: изменено
- **possible_prestige_goods**: изменено
- **prosperity_modifier**: изменено
- **extension_building_types**: убрано
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/finland_nokia.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_UUSIMAA`
- **building_types**: [[tr/Здания/Бумажные фабрики|Бумажные фабрики]], [[tr/Здания/Лесозаготовки|Лесозаготовки]], [[tr/Здания/Электростанции|Электростанции]], [[tr/Здания/Электрозаводы|Электрозаводы]]
- **possible_prestige_goods**: `prestige_good_nokia_phones`
- **potential**: скрипт, строки 108–110
- **attainable**: скрипт, строки 112–118
- **possible**: скрипт, строки 120–130
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.05` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
  - [[vanilla/движок/Модификаторы B#^m-building-synthetics-plant-throughput-add|building_synthetics_plant_throughput_add]] = `0.05` → [[tr/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 137–143
- **ai_construction_targets**: скрипт, строки 145–152
- **ai_weight**: скрипт, строки 154–156
