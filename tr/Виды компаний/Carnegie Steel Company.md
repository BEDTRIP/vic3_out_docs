---
type: concept
description: "Вид компании «Carnegie Steel Company» — T&R 1.13, `company_us_steel`"
project: vic3
source: tr
aliases: ["Carnegie Steel Company", "company_us_steel"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_us_steel
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_usa.txt]
replaces: "[[vanilla/Виды компаний/Carnegie Steel Company]]"
---
# Carnegie Steel Company

Вид компании · `company_us_steel` · `common/company_types/ztr_companies_usa.txt:27` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **building_types**: вставка в блок
- **extension_building_types**: вставка в блок
- **prosperity_modifier**: вставка в блок

## Поля

- **building_types**: [[tr/Здания/Alloys Plants|Alloys Plants]]
- **extension_building_types**: [[tr/Здания/Common Ores Mines|Common Ores Mines]], [[tr/Здания/Copper Mines|Copper Mines]]
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-railway-throughput-add|building_railway_throughput_add]] = `-0.05` → [[tr/Здания/Железные дороги|Железные дороги]]
  - `building_aircraft_industry_throughput_add` = `0.05` → [[tr/Здания/Aerospace Industries|Aerospace Industries]]
  - [[vanilla/движок/Модификаторы B#^m-building-shipyard-throughput-add|building_shipyard_throughput_add]] = `0.1` → [[tr/Здания/верфи|верфи]]
