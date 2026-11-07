---
type: concept
description: "Метод производства «Electric Pumped Water» — T&R 1.13, `pm_electric_pumped_water`"
project: vic3
source: tr
aliases: ["Electric Pumped Water", "pm_electric_pumped_water"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electric_pumped_water
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electric Pumped Water

Метод производства · `pm_electric_pumped_water` · `common/production_methods/ztr_new_production_methods.txt:6425`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electric_pumped_water.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Пневматические инструменты|Пневматические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `40` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `30` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_water_add` = `135` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `800` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `400` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Water|Water]]
