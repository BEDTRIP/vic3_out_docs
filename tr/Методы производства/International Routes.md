---
type: concept
description: "Метод производства «International Routes» — T&R 1.13, `pm_international_routes`"
project: vic3
source: tr
aliases: ["International Routes", "pm_international_routes"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_international_routes
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# International Routes

Метод производства · `pm_international_routes` · `common/production_methods/ztr_modified_mr_production_methods.txt:584`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_travel_4.dds`
- **unlocking_technologies**: [[tr/Технологии/International Travel|International Travel]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_civil_planes_add` = `15` → [[tr/Товары/Airplanes|Airplanes]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `3` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `120` → [[vanilla/Товары/Перевозка|Перевозка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-merchant-marine-add|goods_output_merchant_marine_add]] = `3` → [[vanilla/Товары/Торговые корабли|Торговые корабли]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `800` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `25`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Flight Type|Flight Type]]
