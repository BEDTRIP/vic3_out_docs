---
type: concept
description: "Метод производства «Conveyor Belt Abattoirs» — T&R 1.13, `pm_conveyor_belt_abattoirs`"
project: vic3
source: tr
aliases: ["Conveyor Belt Abattoirs", "pm_conveyor_belt_abattoirs"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_conveyor_belt_abattoirs
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Conveyor Belt Abattoirs

Метод производства · `pm_conveyor_belt_abattoirs` · `common/production_methods/ztr_agriculture_production_methods.txt:236`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_conveyor_belt_abattoirs.dds`
- **unlocking_technologies**: [[tr/Технологии/Mechanical Arms|Mechanical Arms]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_lubricant_add` = `2` → [[tr/Товары/Lubricants|Lubricants]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `85` → [[vanilla/Товары/Мясо|Мясо]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `1750` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_livestock_ranch)|Основа (pmg_base_building_livestock_ranch)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Интенсивный сбор шерсти|Интенсивный сбор шерсти]]
