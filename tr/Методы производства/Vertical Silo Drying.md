---
type: concept
description: "Метод производства «Vertical Silo Drying» — T&R 1.13, `pm_vertical_silo_drying`"
project: vic3
source: tr
aliases: ["Vertical Silo Drying", "pm_vertical_silo_drying"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_vertical_silo_drying
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Vertical Silo Drying

Метод производства · `pm_vertical_silo_drying` · `common/production_methods/ztr_agriculture_production_methods.txt:894`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_vertical_silo_drying.dds`
- **unlocking_technologies**: [[tr/Технологии/Green Revolution|Green Revolution]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coffee-add|goods_output_coffee_add]] = `20` → [[vanilla/Товары/Кофе|Кофе]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
  - **unscaled**: пусто

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Метод сушки|Метод сушки]]
