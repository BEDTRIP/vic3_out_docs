---
type: concept
description: "Метод производства «Internet (pm_internet_building_datacenter)» — T&R 1.13, `pm_internet_building_datacenter`"
project: vic3
audience: agent
source: tr
aliases: ["Internet (pm_internet_building_datacenter)", "Internet", "pm_internet_building_datacenter"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_building_datacenter
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Internet (pm_internet_building_datacenter)

Метод производства · `pm_internet_building_datacenter` · `common/production_methods/ztr_data_production_methods.txt:702`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_building_office.dds`
- **unlocking_technologies**: [[tr/Технологии/Internet|Internet]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_raw_data_add` = `-20` → [[tr/Товары/Raw Data|Raw Data]]
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_processors_add` = `0.5` → [[tr/Товары/Processors|Processors]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-125` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Transportation (pmg_data_transportation_building_datacenter)|Data Transportation (pmg_data_transportation_building_datacenter)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Cloud Storage|Cloud Storage]]
