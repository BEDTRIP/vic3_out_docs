---
type: concept
description: "Метод производства «HV Distribution» — T&R 1.13, `pm_hv_grid_download`"
project: vic3
audience: agent
source: tr
aliases: ["HV Distribution", "pm_hv_grid_download"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hv_grid_download
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# HV Distribution

Метод производства · `pm_hv_grid_download` · `common/production_methods/ztr_energy_production_methods.txt:1475`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hv_distribution.dds`
- **unlocking_technologies**: [[tr/Технологии/HV Transmission|HV Transmission]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_global_electricity_add` = `400` → [[tr/Товары/National Electricity|National Electricity]]
    - `goods_input_copperwires_add` = `15` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `450` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
- **disallowing_laws**: [[tr/Законы/Local Electricity Systems|Local Electricity Systems]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Grid Operation|Grid Operation]]
