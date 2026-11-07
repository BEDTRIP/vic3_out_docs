---
type: concept
description: "Метод производства «Local Data Storage» — T&R 1.13, `pm_local_data_storage_building_datacenter`"
project: vic3
audience: agent
source: tr
aliases: ["Local Data Storage", "pm_local_data_storage_building_datacenter"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_local_data_storage_building_datacenter
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Local Data Storage

Метод производства · `pm_local_data_storage_building_datacenter` · `common/production_methods/ztr_data_production_methods.txt:549`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_local_data_storage_building_datacenter.dds`
- **unlocking_technologies**: [[tr/Технологии/Digital Infrastructure|Digital Infrastructure]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_raw_data_add` = `300` → [[tr/Товары/Raw Data|Raw Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `5` → [[tr/Товары/Water|Water]]
    - `goods_output_organized_data_add` = `300` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Type of Datacenter|Type of Datacenter]]
