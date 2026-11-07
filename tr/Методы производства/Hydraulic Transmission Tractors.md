---
type: concept
description: "Метод производства «Hydraulic Transmission Tractors» — T&R 1.13, `pm_hydraulic_transmission_tractors_building_rice_farm`"
project: vic3
audience: agent
source: tr
aliases: ["Hydraulic Transmission Tractors", "pm_hydraulic_transmission_tractors_building_rice_farm"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hydraulic_transmission_tractors_building_rice_farm
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Hydraulic Transmission Tractors

Метод производства · `pm_hydraulic_transmission_tractors_building_rice_farm` · `common/production_methods/ztr_agriculture_production_methods.txt:3`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/compression_ignition_tractors.dds`
- **unlocking_technologies**: [[tr/Технологии/Green Revolution|Green Revolution]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `1` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_water_add` = `1` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-5000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Процесс сбора урожая (pmg_harvesting_process_building_rice_farm)|Процесс сбора урожая (pmg_harvesting_process_building_rice_farm)]]
