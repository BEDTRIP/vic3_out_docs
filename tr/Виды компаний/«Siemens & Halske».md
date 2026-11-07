---
type: concept
description: "Вид компании ««Siemens & Halske»» — T&R 1.13, `company_siemens_and_halske`"
project: vic3
source: tr
aliases: ["«Siemens & Halske»", "Siemens & Halske", "company_siemens_and_halske"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_siemens_and_halske
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_germany.txt]
replaces: "[[vanilla/Виды компаний/«Siemens & Halske»]]"
---
# «Siemens & Halske»

Вид компании · `company_siemens_and_halske` · `common/company_types/ztr_companies_germany.txt:22` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **building_types**: вставка в блок
- **extension_building_types**: вставка в блок
- **prosperity_modifier**: вставка в блок

## Поля

- **building_types**: [[tr/Здания/Robotics Industries|Robotics Industries]]
- **extension_building_types**: [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **prosperity_modifier**:
  - `building_electronics_industry_throughput_add` = `0.05` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
  - [[vanilla/движок/Модификаторы B#^m-building-electrics-industry-throughput-add|building_electrics_industry_throughput_add]] = `0.05` → [[tr/Здания/Электрозаводы|Электрозаводы]]
