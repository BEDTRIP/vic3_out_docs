---
type: concept
description: "Метод производства «Local Network (pm_local_network_building_office)» — T&R 1.13, `pm_local_network_building_office`"
project: vic3
source: tr
aliases: ["Local Network (pm_local_network_building_office)", "Local Network", "pm_local_network_building_office"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_local_network_building_office
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Local Network (pm_local_network_building_office)

Метод производства · `pm_local_network_building_office` · `common/production_methods/ztr_data_production_methods.txt:496`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_local_network_building_office.dds`
- **unlocking_technologies**: [[tr/Технологии/Networking Protocols|Networking Protocols]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_processors_add` = `0.5` → [[tr/Товары/Processors|Processors]]
    - `goods_input_telecommunications_add` = `3` → [[tr/Товары/Telecommunications|Telecommunications]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `-400` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Transportation (pmg_data_transportation_building_office)|Data Transportation (pmg_data_transportation_building_office)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Version Control|Version Control]]
