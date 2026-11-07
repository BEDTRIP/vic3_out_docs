---
type: concept
description: "Метод производства «Insulated Packaging» — T&R 1.13, `pm_insulated_packaging`"
project: vic3
audience: agent
source: tr
aliases: ["Insulated Packaging", "pm_insulated_packaging"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_insulated_packaging
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Insulated Packaging

Метод производства · `pm_insulated_packaging` · `common/production_methods/ztr_new_production_methods.txt:7287`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_insulated_packaging.dds`
- **unlocking_technologies**: [[tr/Технологии/Supermarket|Supermarket]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fish-add|goods_input_fish_add]] = `25` → [[vanilla/Товары/Рыба|Рыба]]
    - `goods_input_aluminium_add` = `10` → [[tr/Товары/Aluminium|Aluminium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-grain-add|goods_input_grain_add]] = `-30` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-meat-add|goods_input_meat_add]] = `25` → [[vanilla/Товары/Мясо|Мясо]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-groceries-add|goods_output_groceries_add]] = `75` → [[vanilla/Товары/Продукты|Продукты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Консервирование|Консервирование]]
