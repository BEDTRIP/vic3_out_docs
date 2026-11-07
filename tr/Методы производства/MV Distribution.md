---
type: concept
description: "Метод производства «MV Distribution» — T&R 1.13, `pm_basic_grid_download`"
project: vic3
audience: agent
source: tr
aliases: ["MV Distribution", "pm_basic_grid_download"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_grid_download
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# MV Distribution

Метод производства · `pm_basic_grid_download` · `common/production_methods/ztr_energy_production_methods.txt:1458`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/lv_distribution.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_global_electricity_add` = `250` → [[tr/Товары/National Electricity|National Electricity]]
    - `goods_input_copperwires_add` = `10` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `250` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Grid Operation|Grid Operation]]
