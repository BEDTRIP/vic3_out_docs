---
type: concept
description: "Метод производства «Mid Publishing Communication» — T&R 1.13, `manzoni_pm_electric_telegraph`"
project: vic3
audience: agent
source: tr
aliases: ["Mid Publishing Communication", "manzoni_pm_electric_telegraph"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_electric_telegraph
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Mid Publishing Communication

Метод производства · `manzoni_pm_electric_telegraph` · `common/production_methods/ztr_modified_mr_production_methods.txt:818`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_transmission_telegraph.dds`
- **unlocking_technologies**: [[tr/Технологии/Электрический телеграф|Электрический телеграф]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_alloys_add` = `2` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `2` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_organized_data_add` = `2` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `250` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Type of Communication|Type of Communication]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Circular Pressure Printing Machine|Circular Pressure Printing Machine]], [[tr/Методы производства/Digital Printers|Digital Printers]], [[tr/Методы производства/Linotype|Linotype]], [[tr/Методы производства/No Broadcast Media Industry|No Broadcast Media Industry]], [[tr/Методы производства/No Digital Media Industry|No Digital Media Industry]], [[tr/Методы производства/Offset Printing|Offset Printing]], [[tr/Методы производства/Printing Presses|Printing Presses]], [[tr/Методы производства/Rotary Press|Rotary Press]]
