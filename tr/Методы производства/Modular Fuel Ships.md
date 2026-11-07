---
type: concept
description: "Метод производства «Modular Fuel Ships» — T&R 1.13, `pm_modular_shipbuilding`"
project: vic3
audience: agent
source: tr
aliases: ["Modular Fuel Ships", "pm_modular_shipbuilding"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modular_shipbuilding
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modular Fuel Ships

Метод производства · `pm_modular_shipbuilding` · `common/production_methods/ztr_new_production_methods.txt:10253`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modular_shipbuilding.dds`
- **unlocking_technologies**: [[tr/Технологии/Modular Shipbuilding|Modular Shipbuilding]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-ship-construction-add|country_ship_construction_add]] = `25`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `15` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_aluminium_add` = `15` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_processors_add` = `5` → [[tr/Товары/Processors|Processors]]
    - `goods_input_robotics_add` = `10` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-steamers-add|goods_output_steamers_add]] = `105` → [[vanilla/Товары/Пароходы|Пароходы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_shipyard)|Основа (pmg_base_building_shipyard)]]
