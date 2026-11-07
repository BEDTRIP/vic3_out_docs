---
type: concept
description: "Метод производства «Regional Routes» — T&R 1.13, `pm_regional_routes`"
project: vic3
audience: agent
source: tr
aliases: ["Regional Routes", "pm_regional_routes"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_regional_routes
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Regional Routes

Метод производства · `pm_regional_routes` · `common/production_methods/ztr_modified_mr_production_methods.txt:517`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_travel_2.dds`
- **unlocking_technologies**: [[tr/Технологии/Двигатель внутреннего сгорания|Двигатель внутреннего сгорания]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_civil_planes_add` = `7` → [[tr/Товары/Airplanes|Airplanes]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `2` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_telecommunications_add` = `4` → [[tr/Товары/Telecommunications|Telecommunications]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `75` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Flight Type|Flight Type]]
