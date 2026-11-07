---
type: concept
description: "Метод производства «Fracking» — T&R 1.13, `pm_gas_hydraulic_fracturing`"
project: vic3
source: tr
aliases: ["Fracking", "pm_gas_hydraulic_fracturing"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gas_hydraulic_fracturing
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Fracking

Метод производства · `pm_gas_hydraulic_fracturing` · `common/production_methods/ztr_new_production_methods.txt:7561`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_gas_fracking.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **unlocking_technologies**: [[tr/Технологии/Fracking|Fracking]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `90` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_robotics_add` = `20` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_water_add` = `20` → [[tr/Товары/Water|Water]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_electricity_add` = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_gas_add` = `290` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_output_oil_add` = `70` → [[vanilla/Товары/ГСМ|ГСМ]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Natural Gas Rig|Natural Gas Rig]]
