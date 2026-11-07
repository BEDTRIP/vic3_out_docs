---
type: concept
description: "Метод производства «Horizontal Perforation (pm_gas_horizontal_perforation)» — T&R 1.13, `pm_gas_horizontal_perforation`"
project: vic3
source: tr
aliases: ["Horizontal Perforation (pm_gas_horizontal_perforation)", "Horizontal Perforation", "pm_gas_horizontal_perforation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gas_horizontal_perforation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Horizontal Perforation (pm_gas_horizontal_perforation)

Метод производства · `pm_gas_horizontal_perforation` · `common/production_methods/ztr_new_production_methods.txt:7526`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_gas_horizontal_drilling.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[tr/Технологии/Horizontal Drilling|Horizontal Drilling]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `50` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_electricity_add` = `25` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_gas_add` = `170` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_output_oil_add` = `30` → [[vanilla/Товары/ГСМ|ГСМ]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Natural Gas Rig|Natural Gas Rig]]
