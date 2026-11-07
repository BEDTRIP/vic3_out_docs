---
type: concept
description: "Метод производства «Internet (pm_internet_building_office)» — T&R 1.13, `pm_internet_building_office`"
project: vic3
source: tr
aliases: ["Internet (pm_internet_building_office)", "Internet", "pm_internet_building_office"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_building_office
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Internet (pm_internet_building_office)

Метод производства · `pm_internet_building_office` · `common/production_methods/ztr_data_production_methods.txt:513`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_building_office.dds`
- **unlocking_technologies**: [[tr/Технологии/Internet|Internet]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_processors_add` = `0.5` → [[tr/Товары/Processors|Processors]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `-500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Transportation (pmg_data_transportation_building_office)|Data Transportation (pmg_data_transportation_building_office)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Agentic Coding|Agentic Coding]], [[tr/Методы производства/Casual Games Development|Casual Games Development]], [[tr/Методы производства/Cloud Based DevOps|Cloud Based DevOps]], [[tr/Методы производства/Cloud Data Processing|Cloud Data Processing]], [[tr/Методы производства/Global Outsourcing Hub|Global Outsourcing Hub]], [[tr/Методы производства/Mobile Apps|Mobile Apps]], [[tr/Методы производства/Version Control|Version Control]], [[tr/Методы производства/Websites|Websites]]
