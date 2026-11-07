---
type: concept
description: "Метод производства «Basic Data Processing» — T&R 1.13, `pm_basic_data_analysis`"
project: vic3
audience: agent
source: tr
aliases: ["Basic Data Processing", "pm_basic_data_analysis"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_data_analysis
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Basic Data Processing

Метод производства · `pm_basic_data_analysis` · `common/production_methods/ztr_data_production_methods.txt:343`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_basic_data_analysis.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Statistics|Modern Statistics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_organized_data_add` = `55` → [[tr/Товары/Organized Data|Organized Data]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `3` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_softwares_add` = `1` → [[tr/Товары/Software|Software]]
    - `goods_output_business_data_add` = `90` → [[tr/Товары/Business Data|Business Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Section|Data Section]]
