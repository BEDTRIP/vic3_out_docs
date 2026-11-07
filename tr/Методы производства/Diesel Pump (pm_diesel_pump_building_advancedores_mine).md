---
type: concept
description: "Метод производства «Diesel Pump (pm_diesel_pump_building_advancedores_mine)» — T&R 1.13, `pm_diesel_pump_building_advancedores_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Diesel Pump (pm_diesel_pump_building_advancedores_mine)", "Diesel Pump", "pm_diesel_pump_building_advancedores_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_advancedores_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Diesel Pump (pm_diesel_pump_building_advancedores_mine)

Метод производства · `pm_diesel_pump_building_advancedores_mine` · `common/production_methods/ztr_new_production_methods.txt:5282`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **unlocking_technologies**: [[tr/Технологии/Silicon|Silicon]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `25`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_light_fuel_add` = `3` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_advancedores_add` = `35` → [[tr/Товары/Advanced Ores|Advanced Ores]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_advancedores_mine)|Mining Equipment (pmg_mining_equipment_building_advancedores_mine)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Dynamite (pm_dynamite_building_advancedores_mine)|Dynamite (pm_dynamite_building_advancedores_mine)]], [[tr/Методы производства/Nitroglycerin (pm_nitroglycerin_building_advancedores_mine)|Nitroglycerin (pm_nitroglycerin_building_advancedores_mine)]]
