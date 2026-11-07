---
type: concept
description: "Метод производства «Electric Fueled Pump (pm_electric_fueled_pump_building_advancedores_mine)» — T&R 1.13, `pm_electric_fueled_pump_building_advancedores_mine`"
project: vic3
source: tr
aliases: ["Electric Fueled Pump (pm_electric_fueled_pump_building_advancedores_mine)", "Electric Fueled Pump", "pm_electric_fueled_pump_building_advancedores_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electric_fueled_pump_building_advancedores_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electric Fueled Pump (pm_electric_fueled_pump_building_advancedores_mine)

Метод производства · `pm_electric_fueled_pump_building_advancedores_mine` · `common/production_methods/ztr_new_production_methods.txt:2485`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/electric_fueled_pump.dds`
- **unlocking_technologies**: [[tr/Технологии/Integrated Circuits|Integrated Circuits]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_tools_add` = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_advancedores_add` = `45` → [[tr/Товары/Advanced Ores|Advanced Ores]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_advancedores_mine)|Mining Equipment (pmg_mining_equipment_building_advancedores_mine)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Dynamite (pm_dynamite_building_advancedores_mine)|Dynamite (pm_dynamite_building_advancedores_mine)]], [[tr/Методы производства/Nitroglycerin (pm_nitroglycerin_building_advancedores_mine)|Nitroglycerin (pm_nitroglycerin_building_advancedores_mine)]]
