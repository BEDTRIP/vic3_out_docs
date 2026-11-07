---
type: concept
description: "Метод производства «Streamlined Trains (pm_advanced_express_trains)» — T&R 1.13, `pm_advanced_express_trains`"
project: vic3
audience: agent
source: tr
aliases: ["Streamlined Trains (pm_advanced_express_trains)", "Streamlined Trains", "pm_advanced_express_trains"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_express_trains
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Streamlined Trains (pm_advanced_express_trains)

Метод производства · `pm_advanced_express_trains` · `common/production_methods/ztr_new_production_methods.txt:8644`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_express_trains.dds`
- **replacement_if_valid**: [[tr/Методы производства/Streamlined Trains (pm_advanced_express_trains_principle_transport_3)|Streamlined Trains (pm_advanced_express_trains_principle_transport_3)]]
- **unlocking_technologies**: [[tr/Технологии/Streamlined Railways|Streamlined Railways]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `3` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_input_aluminium_add` = `2` → [[tr/Товары/Aluminium|Aluminium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `2` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `60` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `150` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `150` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `70`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_railway)|Основа (pmg_base_building_railway)]]
