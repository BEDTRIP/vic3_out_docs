---
type: concept
description: "Метод производства «Hydraulic Fracturing» — T&R 1.13, `pm_oil_hydraulic_fracturing`"
project: vic3
audience: agent
source: tr
aliases: ["Hydraulic Fracturing", "pm_oil_hydraulic_fracturing"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_oil_hydraulic_fracturing
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Hydraulic Fracturing

Метод производства · `pm_oil_hydraulic_fracturing` · `common/production_methods/ztr_new_production_methods.txt:7384`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_oil_fracking.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[tr/Технологии/Fracking|Fracking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `120` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_robotics_add` = `25` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_water_add` = `35` → [[tr/Товары/Water|Water]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-oil-add|goods_output_oil_add]] = `350` → [[vanilla/Товары/ГСМ|ГСМ]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_oil_rig)|Основа (pmg_base_building_oil_rig)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/CO2-EOR Storage|CO2-EOR Storage]]
