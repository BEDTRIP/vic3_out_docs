---
type: concept
description: "Вид компании ««Ford Motor Company»» — T&R 1.13, `company_ford_motor`"
project: vic3
source: tr
aliases: ["«Ford Motor Company»", "Ford Motor Company", "company_ford_motor"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ford_motor
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_companies_usa.txt]
replaces: "[[vanilla/Виды компаний/«Ford Motor Company»]]"
---
# «Ford Motor Company»

Вид компании · `company_ford_motor` · `common/company_types/ztr_companies_usa.txt:135` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **extension_building_types**: вставка в блок
- **prosperity_modifier**: вставка в блок

## Поля

- **extension_building_types**: [[tr/Здания/Aerospace Industries|Aerospace Industries]]
- **prosperity_modifier**:
  - `building_motor_industry_throughput_add` = `-0.1` → [[tr/Здания/Моторные заводы|Моторные заводы]]
  - `building_automotive_industry_throughput_add` = `-0.05` → [[tr/Здания/Автомобильные заводы|Автомобильные заводы]]
  - `building_mendelejew_hydrogenation_plants_throughput_add` = `0.1` → [[tr/Здания/Oil Refineries|Oil Refineries]]
  - `state_infrastructure_from_automobiles_consumption_add` = `0.15`
  - `building_group_bg_light_industry_throughput_add` = `0.01`
  - `building_railway_throughput_add` = `-0.2` → [[tr/Здания/Железные дороги|Железные дороги]]
