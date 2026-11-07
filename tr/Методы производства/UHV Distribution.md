---
type: concept
description: "Метод производства «UHV Distribution» — T&R 1.13, `pm_uhv_grid_download`"
project: vic3
source: tr
aliases: ["UHV Distribution", "pm_uhv_grid_download"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_uhv_grid_download
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# UHV Distribution

Метод производства · `pm_uhv_grid_download` · `common/production_methods/ztr_energy_production_methods.txt:1501`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/uhv_distribution.dds`
- **unlocking_technologies**: [[tr/Технологии/Embedded Control Systems|Embedded Control Systems]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_global_electricity_add` = `425` → [[tr/Товары/National Electricity|National Electricity]]
    - `goods_input_copperwires_add` = `20` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `500` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **disallowing_laws**: [[tr/Законы/Local Electricity Systems|Local Electricity Systems]], [[tr/Законы/National Electricity System|National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Grid Operation|Grid Operation]]
