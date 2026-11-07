---
type: concept
description: "Метод производства «3D Printed Tools» — T&R 1.13, `pm_3d_printed_tools`"
project: vic3
audience: agent
source: tr
aliases: ["3D Printed Tools", "pm_3d_printed_tools"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_3d_printed_tools
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# 3D Printed Tools

Метод производства · `pm_3d_printed_tools` · `common/production_methods/ztr_new_production_methods.txt:6344`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_3d_printed_tools.dds`
- **unlocking_technologies**: [[tr/Технологии/Additive Manufacturing|Additive Manufacturing]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-rubber-add|goods_input_rubber_add]] = `10` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_copperwires_add` = `5` → [[tr/Товары/Wires|Wires]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `15` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-tools-add|goods_output_tools_add]] = `145` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_tooling_workshop)|Основа (pmg_base_building_tooling_workshop)]]
