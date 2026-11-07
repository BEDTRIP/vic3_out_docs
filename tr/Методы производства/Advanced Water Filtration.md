---
type: concept
description: "Метод производства «Advanced Water Filtration» — T&R 1.13, `pm_advanced_water_filtration`"
project: vic3
audience: agent
source: tr
aliases: ["Advanced Water Filtration", "pm_advanced_water_filtration"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_water_filtration
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Water Filtration

Метод производства · `pm_advanced_water_filtration` · `common/production_methods/ztr_new_production_methods.txt:6452`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_water_filtration.dds`
- **unlocking_technologies**: [[tr/Технологии/Advanced Water Depuration|Advanced Water Depuration]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `30` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `60` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `45` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_electroniccomponents_add` = `15` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_water_add` = `180` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `400` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Water|Water]]
