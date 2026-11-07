---
type: concept
description: "Метод производства «Diesel Pump (pm_diesel_pump_building_bauxite_mine)» — T&R 1.13, `pm_diesel_pump_building_bauxite_mine`"
project: vic3
source: tr
aliases: ["Diesel Pump (pm_diesel_pump_building_bauxite_mine)", "Diesel Pump", "pm_diesel_pump_building_bauxite_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_bauxite_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Diesel Pump (pm_diesel_pump_building_bauxite_mine)

Метод производства · `pm_diesel_pump_building_bauxite_mine` · `common/production_methods/ztr_new_production_methods.txt:5484`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `25`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_light_fuel_add` = `3` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_bauxite_add` = `85` → [[tr/Товары/Bauxite|Bauxite]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_bauxite_mine)|Mining Equipment (pmg_mining_equipment_building_bauxite_mine)]]
