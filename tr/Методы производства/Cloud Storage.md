---
type: concept
description: "Метод производства «Cloud Storage» — T&R 1.13, `pm_cloud_storage_building_datacenter`"
project: vic3
source: tr
aliases: ["Cloud Storage", "pm_cloud_storage_building_datacenter"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cloud_storage_building_datacenter
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Cloud Storage

Метод производства · `pm_cloud_storage_building_datacenter` · `common/production_methods/ztr_data_production_methods.txt:569`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_cloud_storage_building_datacenter.dds`
- **unlocking_technologies**: [[tr/Технологии/Cloud Computing|Cloud Computing]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_raw_data_add` = `450` → [[tr/Товары/Raw Data|Raw Data]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_water_add` = `10` → [[tr/Товары/Water|Water]]
    - `goods_output_organized_data_add` = `450` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_datacenter)|Internet (pm_internet_building_datacenter)]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Type of Datacenter|Type of Datacenter]]
