---
type: concept
description: "Метод производства «Polyester» — T&R 1.13, `pm_polyester`"
project: vic3
source: tr
aliases: ["Polyester", "pm_polyester"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_polyester
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Polyester

Метод производства · `pm_polyester` · `common/production_methods/ztr_new_production_methods.txt:10076`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/polyester.dds`
- **unlocking_technologies**: [[tr/Технологии/Polyester Synthesis|Polyester Synthesis]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_heavy_fuel_add` = `3` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-dye-add|goods_output_dye_add]] = `-10` → [[vanilla/Товары/Красители|Красители]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fertilizer-add|goods_output_fertilizer_add]] = `-15` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silk-add|goods_output_silk_add]] = `55` → [[vanilla/Товары/Шёлк|Шёлк]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `250` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Синтетический краситель|Синтетический краситель]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Синтетический шёлк|Синтетический шёлк]]
