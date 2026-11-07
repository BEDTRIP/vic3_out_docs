---
type: concept
description: "Метод производства «Cloud Data Processing» — T&R 1.13, `pm_cloud_databased_data_analysis`"
project: vic3
source: tr
aliases: ["Cloud Data Processing", "pm_cloud_databased_data_analysis"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_cloud_databased_data_analysis
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Cloud Data Processing

Метод производства · `pm_cloud_databased_data_analysis` · `common/production_methods/ztr_data_production_methods.txt:368`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_cloud_databased_data_analysis.dds`
- **unlocking_technologies**: [[tr/Технологии/Cloud Computing|Cloud Computing]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet (pm_internet_building_office)|Internet (pm_internet_building_office)]], [[tr/Методы производства/Smartworking|Smartworking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `70` → [[tr/Товары/Organized Data|Organized Data]]
    - `goods_input_computer_add` = `4` → [[tr/Товары/Computers|Computers]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_softwares_add` = `4` → [[tr/Товары/Software|Software]]
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_output_business_data_add` = `120` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Section|Data Section]]
