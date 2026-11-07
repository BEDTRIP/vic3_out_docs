---
type: concept
description: "Метод производства «Gas Combustion Derrick» — T&R 1.13, `pm_gas_combustion_derricks`"
project: vic3
audience: agent
source: tr
aliases: ["Gas Combustion Derrick", "pm_gas_combustion_derricks"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gas_combustion_derricks
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Gas Combustion Derrick

Метод производства · `pm_gas_combustion_derricks` · `common/production_methods/ztr_new_production_methods.txt:7492`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_gas_combustion_derricks.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[tr/Технологии/Gas Turbine|Gas Turbine]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `15` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_gas_add` = `95` → [[tr/Товары/Natural Gas|Natural Gas]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-oil-add|goods_output_oil_add]] = `10` → [[vanilla/Товары/ГСМ|ГСМ]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Natural Gas Rig|Natural Gas Rig]]
