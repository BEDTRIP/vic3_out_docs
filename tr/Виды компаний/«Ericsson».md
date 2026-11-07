---
type: concept
description: "Вид компании ««Ericsson»» — T&R 1.13, `company_ericsson`"
project: vic3
source: tr
aliases: ["«Ericsson»", "Ericsson", "company_ericsson"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ericsson
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_europe.txt]
replaces: "[[vanilla/Виды компаний/«Ericsson»]]"
---
# «Ericsson»

Вид компании · `company_ericsson` · `common/company_types/ztr_companies_europe.txt:46` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **building_types**: вставка в блок
- **extension_building_types**: вставка в блок
- **prosperity_modifier**: вставка в блок

## Поля

- **building_types**: [[tr/Здания/Battery Plants|Battery Plants]], [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **extension_building_types**: [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **prosperity_modifier**:
  - `building_telecommunications_industry_throughput_add` = `0.1` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
