---
type: concept
description: "Метод производства «Post-war Vehicles» — T&R 1.13, `pm_modern_vehicles_production`"
project: vic3
source: tr
aliases: ["Post-war Vehicles", "pm_modern_vehicles_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modern_vehicles_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Post-war Vehicles

Метод производства · `pm_modern_vehicles_production` · `common/production_methods/ztr_new_production_methods.txt:2212`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modern_vehicles_production.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`
- **unlocking_technologies**: [[tr/Технологии/Modern Vehicles|Modern Vehicles]]
- **unlocking_production_methods**: [[tr/Методы производства/Конвейерное производство (pm_assembly_lines_building_automotive_industry)|Конвейерное производство (pm_assembly_lines_building_automotive_industry)]], [[tr/Методы производства/Advanced Assembly Lines (pm_advanced_assembly_lines_building_automotive_industry)|Advanced Assembly Lines (pm_advanced_assembly_lines_building_automotive_industry)]], [[tr/Методы производства/Robotic Assembly Lines (pm_robotic_building_automotive_industry)|Robotic Assembly Lines (pm_robotic_building_automotive_industry)]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `25` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-rubber-add|goods_input_rubber_add]] = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_light_fuel_add` = `15` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_copperwires_add` = `5` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-dye-add|goods_input_dye_add]] = `5` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_aluminium_add` = `10` → [[tr/Товары/Aluminium|Aluminium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-automobiles-add|goods_output_automobiles_add]] = `50` → [[tr/Товары/Автомобили|Автомобили]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство автомобилей|Производство автомобилей]]
