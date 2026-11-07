---
type: concept
description: "Вид компании «LKAB» — T&R 1.13, `company_lkab`"
project: vic3
source: tr
aliases: ["LKAB", "company_lkab"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_lkab
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_europe.txt]
replaces: "[[vanilla/Виды компаний/LKAB]]"
---
# LKAB

Вид компании · `company_lkab` · `common/company_types/ztr_companies_europe.txt:63` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **building_types**: вставка в блок
- **extension_building_types**: вставка в блок
- **prosperity_modifier**: вставка в блок

## Поля

- **building_types**: [[tr/Здания/Copper Mines|Copper Mines]]
- **extension_building_types**: [[tr/Здания/Common Ores Mines|Common Ores Mines]], [[tr/Здания/Alloys Plants|Alloys Plants]], [[tr/Здания/Bauxite Mines|Bauxite Mines]]
- **prosperity_modifier**:
  - `building_iron_mine_throughput_add` = `-0.1` → [[tr/Здания/Железные рудники|Железные рудники]]
  - `building_copper_mine_throughput_add` = `0.1` → [[tr/Здания/Copper Mines|Copper Mines]]
